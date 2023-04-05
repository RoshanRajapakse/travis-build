# frozen_string_literal: true

source 'https://rubygems.org'

if ENV.key?('DYNO')
  ruby File.read(File.expand_path('.ruby-version', __dir__)).strip
end

def gh(slug)
  "https://github.com/#{slug}"
end

gem 'activesupport', '~> 6.1', '>= 6.1.7.3'
gem 'addressable', '~> 2.8', '>= 2.8.0'
gem 'codeclimate-test-reporter', require: false, group: %i[development test]
gem 'coder'
gem 'connection_pool'
gem 'faraday'
gem 'faraday_middleware'
gem 'jemalloc', git: gh('joshk/jemalloc-rb')
gem 'jwt', '~> 1.5'
gem 'metriks', '0.9.9.6'
gem 'metriks-librato_metrics', git: gh('eric/metriks-librato_metrics')
gem 'minitar'
gem 'mocha', require: false, group: %i[development test]
gem 'parallel_tests', require: false, group: %i[development test]
gem 'pry', require: false, group: %i[development test]
gem 'webmock', group: :test
gem 'puma', '>= 4.3.12'
gem 'rack', '>= 3.0.0'
gem 'rack-ssl', '~> 1.4', '>= 1.4.1'
gem 'rack-test', '>= 2.0.0'
gem 'rake'
gem 'rbtrace'
gem 'rerun', require: false, group: :development
gem 'rspec', '~> 3.0', group: %i[development test]
gem 'rubocop', require: false, group: %i[development test]
gem 'sentry-raven'
gem 'simplecov', require: false, group: %i[development test]
gem 'sinatra', '>= 2.2.3'
gem 'sinatra-contrib', '>= 2.2.3'
gem 'travis'
gem 'travis-config'
gem 'travis-github_apps', git: gh('travis-ci/travis-github_apps')
gem 'travis-rollout', git: gh('travis-ci/travis-rollout')
gem 'travis-support', git: gh('travis-ci/travis-support')

gem "octokit", "~> 4.18", ">= 4.18.0"
gem 'rest-client'
