# A sample Guardfile
# More info at https://github.com/guard/guard#readme
require 'jekyll'

guard 'jekyll-plus', serve: true, drafts:true do
  watch /.*/
  ignore /^_site/
end

guard 'livereload' do
  watch /^_site/
end