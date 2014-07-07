Install Xcode from appstore

xcode-select --install

// Follow those steps: http://railsapps.github.io/installrubyonrails-mac.html

// config GIT
git config --global user.name "Klemen Nagode"
git config --global user.email "klemen.nagode@gmail.com"


// install homebrew
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

// install RVM

\curl -L https://get.rvm.io | bash -s stable --ruby

// update gems
gem update --system

// do not download documentation with gems
echo "gem: --no-document" >> ~/.gemrc

// install rails 
gem install rails

brew install libxml2 libxslt
brew link libxml2 libxslt
gem install nokogiri

// install forman (if needed)
gem install foreman

Install Sublime 3 (beta)

For postgres install: http://postgresapp.com/
For Postgres administration use: pgadmin (I use version 1.18.1
