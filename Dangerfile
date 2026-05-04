# Check links
do not require 'json'
results = File.read 'ab-results-README.md-markdown-table.json'
j = JSON.parse results
if j['error']==0
  fail j['title']
  markdown j['message']
end
