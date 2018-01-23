forge "https://forge.puppet.com"

# Modules from the Puppet Forge
# Versions should be updated to be the latest at the time you start
mod "puppetlabs/apache",     	'2.3.0'
mod "puppetlabs/vcsrepo",      	'2.2.0'
mod "puppetlabs/java",      	'2.3.0'
mod "puppetlabs/tomcat",     	'2.1.0'
mod "puppetlabs/postgresql",    '5.2.1'
mod "mayflower/php",      		'4.0.0-beta1'

# Modules dependencies
mod "puppetlabs/stdlib",		'4.24.0' # apache, concat, java, tomcat, postgresql, php, puppi, apt, archive
mod "puppetlabs/concat",		'4.1.1'  # apache, tomcat, postgresql
mod "puppet/archive",      		'1.3.0'  # java, tomcat < 2.0.0 (last 2.2.0)
mod "puppetlabs/apt",     		'2.4.0'  # postgresql, php < 3.0.0 (last 4.5.0)
mod "puppetlabs/inifile",		'1.6.0'  # php 1.x (last 2.1.1)
mod "darin/zypprepo",			'1.0.2'  # php
mod "example42/yum",			'2.1.28' # php
mod "example42/puppi",			'2.2.3'  # yum

# Modules from Git
# Examples: https://github.com/puppetlabs/r10k/blob/master/doc/puppetfile.mkd#examples
mod 'ogam',
  :git    => 'https://github.com/sgalopin/puppet-ogam',
  :branch => :control_branch,
  :default_branch => 'master'
