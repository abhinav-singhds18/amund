# amund
# index.tsx/searchbar
 const subTextClass = `subtext body-secondary-3 ${this.state.subTextClassName}`;
    return (
      <div id="search-bar">
        <form className="search-bar-form" onSubmit={this.handleValueSubmit}>
          <label>Email address</label>
          <input
            id="search-input"
            className="h2 search-bar-input form-control"
            value={this.state.searchTerm}
            onChange={this.handleValueChange}
            aria-label={this.props.placeholder}
            placeholder={this.props.placeholder}
            autoFocus={true}
            type = "password"
          />
          
          {/* <button className="btn btn-flat-icon search-bar-button" type="submit">
            <img className="icon icon-search" />
          </button> */}
        </form>
        {/* <div className={subTextClass}>
          {this.state.subText}
        </div> */}
      </div>
    );
    
#---------------index.tsx/homepage-----------------#

return (
      <div className="container home-page">
      <div className="row">
        <div className="col-xs-12 col-md-offset-1 col-md-10">
          <SearchBar />
        </div>
        <div className="col-xs-12 col-md-offset-1 col-md-10">
          <SearchBar />

          {/*  <div className="home-element-container">
            <MyBookmarks />
          </div>
          <div className="home-element-container">
            <PopularTables />
          </div> */}
        </div>
      </div>
    </div>
    );
