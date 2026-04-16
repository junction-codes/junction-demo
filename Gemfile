source "https://rubygems.org"

gem "junction-codes", git: "https://github.com/junction-codes/junction.git", branch: "main"
gem "junction-github", git: "https://github.com/junction-codes/junction-github.git", branch: "main"
gem "opentelemetry-exporter-otlp", "~> 0.32"
gem "opentelemetry-instrumentation-all", "~> 0.90"
gem "opentelemetry-sdk", "~> 1.11"
gem "propshaft"
gem "puma"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Audits gems for known security defects (use config/bundler-audit.yml to ignore issues)
  gem "bundler-audit", require: false

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
end
