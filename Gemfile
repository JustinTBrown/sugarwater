# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "3.3.12"
# gem "middleman-cli"

# Live-reloading plugin
gem "middleman-livereload"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end

gem "haml"
gem "html2haml"
gem 'middleman-s3_sync', '~> 3.3'
gem 'mime-types'