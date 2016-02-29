# Did CLI
Unoffical CLI for didthistoday.com

### Installation
Download the binary and move it into your $PATH with the following command

	wget https://raw.githubusercontent.com/Raz0rwire/did-cli/master/did &&
	chmod +x did &&
	mv did /usr/local/bin/did



### Configuration
Create a `~/.didrc` in your home folder containing at least an API Key and optionally an env variable

	DTT_API_KEY={api_key}
    DTT_ENV={dev or prod}

### Usage
Here's a list of all currently supported features of didthistoday.com, it's currently full featured check the API documentation here: http://didthistoday.com/api/doc/

##### Help
    did -h
    did --help

##### Get all your teams
    did teams

##### Get all your tags
    did tags
    
    
##### List your dids
    did list
    
    did --page=2 list
    did -p 2 list
    
    did --page=2 --count=80 list
    did -p 2 -c 80 list    
    
##### Create new did
    did -m "I just created a new did #yay"
    did --message "I just created a new did #yay"
    

### Contributors
    
    