desc "Generate html"
task :html do
  system <<-EOS
    bundle exec asciidoctor --trace \
    -r asciidoctor-diagram \
    -r asciidoctor-diagram-d3js \
    -o sample.html sample.adoc
  EOS
end

task default: :html
