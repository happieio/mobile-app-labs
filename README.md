# ionic-tabs

### Pocket Chip Setup Instructions

- Create ionic.io account [here](https://apps.ionic.io/signup)
- Create github account [here](https://github.com/join)

Run the following commands
    
    curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
    sudo apt-get install -y nodejs
    sudo apt-get install -y build-essential
    sudo npm install cordova -g
    sudo npm install ionic -g
    sudo apt-get install git
    cd ~/ ... mkdir Apps ... cd Apps ... 
    cd ~/ ... git clone https://github.com/happieio/ionic-tabs.git
    cd ionic-tabs ... sudo npm rebuild node-sass
    sudo apt-get install emacs
    
    //may need to run
    sudo npm install caniuse-lite
    
install tide
etc/emacs24/package.el add 
https://github.com/ananthakumaran/tide

#### add project to ionic io
    ionic io init
    ionic upload
    
    
    
    
### Useful Commands

start a web server in a directory
    
    python -m SimpleHTTPServer 8000

fully compile the app and prep for upload
    
    npm run build

just run typescript complication, to check for errors(run from project root)
    
    ./node_modules/.bin/tsc
    
    

    
