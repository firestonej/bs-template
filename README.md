(No longer used in favor of Susy/Breakpoint. See the susy-template repo.)

This is just a simple repo containing the basic stuff I like to have on hand for a new RWD prototype.

To get started is pretty easy:
- Clone the repo
- Open a new terminal window in the repo directory, then:
    cd style && npm install && grunt watch
- Put your custom less in the five non-standard Bootstrap files in the less directory:
- app.less: the mobile-up custom style file.
- sm.less: small screens (768-992px by default)
- md.less: medium screens (992px-1200px by default)
- big.less: big screens (1200px+ by default)
- ie8.less: overrides for IE; use the body classes set in index.html.
