# dealer.js
Dealer.js is web card dealer to generate dynamic personalized card stacks for modular websites

# Features

Integrates into website by just including Javascript

Automatically serves cards stacks/content based on trends, user preferences, ad preferences, location, device type, resolution, referrer and much more
Based on peer-to-peer file assisted delivery
Serves content and block content on like peers preferences
Falls back to the original file host when peers are not available
Configurable hashing methods allow you to adjust file security
Supports any format displayable on webpage
Intelligently chunks files and downloads from multiple peers when available
Optimized for low-latency applications
Local caching for all content
Built on WebRTC DataChannels, found in Chrome, Firefox, and even Chrome for Android and many more browsers soon. Gracefully fallsback in unsupported browsers
Support for streaming HTML5 video
Support for larger files

#Building:

Dealer.js is under heavy development. We don't recommend trying to run it yourself yet.

npm install -d

node bin/build.js
Running:

<script src="dist/dealer.js"></script>

Thanks for checking out PeerKit. We're working on improving documentation and code comments.
#http://dealerjs.com

