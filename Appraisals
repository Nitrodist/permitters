appraise 'rails_4.0.x' do
  gem 'rails', '>= 4.0.0.rc1'
  # includes its own strong parameters and get errors if we include it
end

# note: Rails 3.2.13 tested/works with SP 0.1.3 and up (through 0.2.x)
# note: Rails 3.1.12 tested/works with SP 0.1.5 and up (through 0.2.x)

appraise "rails_3.2.x_with_strong_parameters_0.2.x" do
  gem 'rails', '~> 3.2.13'
  gem 'strong_parameters', '~> 0.2.1'
end

appraise "rails_3.2.x_with_strong_parameters_edge" do
  gem 'rails', '~> 3.2.13'
  gem 'strong_parameters', :git => 'git://github.com/rails/strong_parameters.git'
end

appraise "rails_3.1.x_with_strong_parameters_0.2.x" do
  gem 'rails', '~> 3.1.12'
  gem 'strong_parameters', '~> 0.2.1'
end

appraise "rails_3.1.x_with_strong_parameters_edge" do
  gem 'rails', '~> 3.1.12'
  gem 'strong_parameters', :git => 'git://github.com/rails/strong_parameters.git'
end
