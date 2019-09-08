source 'https://rubygems.org'

gemspec

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'vagrant', '2.2.5',
      git: 'https://github.com/hashicorp/vagrant.git',
      ref: 'v2.2.5'
  gem 'github_changelog_generator',
      git: 'https://github.com/github-changelog-generator/github-changelog-generator.git',
      ref: 'v1.15.0.pre.rc'
end
