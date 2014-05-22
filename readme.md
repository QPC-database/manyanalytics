# multiGA
### A tool for running the same Google Analytics query across multiple websites.

Google  provdes the handy [Google Analytics Query Explorer] (http://ga-dev-tools.appspot.com/explorer/) which is great for building all kinds of queries for Google Analytics. It even lets you select which of your analytics views (or properties) to run the query on. For many agencies or developers managing multiple sites, it is still a chore to run that same query on mutiple sites.

From personal experience, the main application I had for this is for getting lots of data tables into CSV format so that I could do further analysis, processing and visualisation outside of GA's own tools.

## Todo List

I have an electronic engineering background and have hacked together this tool using Javascript and Google's 'hello_analytics_API' example as a starting point. There is still a lot of basic functionality needed to make this more usable and any contributions would be appreciated:

* A way to run queries successively in the same session (currently you have to refresh the page to run a new query and enter the parameters again)
* A way to save query paramters for use later
* A mechanism to browse and select which websites to run query on
* A better user interface!
* (Eventually) a way to run the same query over multiple date ranges - would be useful for reporting e.g. monthly aggregated data for the past year.

Any other suggestions welcome: albert.kawmi@gmail.com

Twitter [@AlbertKawmi] (http://twitter.com/albertkawmi)