using 

# python

url = "https://gist.githubusercontent.com/operatorequals/ee5049677e7bbc97af2941d1d3f04ace/raw/e55fa867d3fb350f70b2897bb415f410027dd7e4"

with httpimport.remote_repo(url):
  import hello

hello.hello()
"#" Hello world

and 

 # github

with httpimport.github_repo('operatorequals', 'httpimport', ref='master'):
  import httpimport as httpimport_upstream
  "#" Also works with 'bitbucket_repo' and 'gitlab_repo'

from "https://github.com/operatorequals/httpimport?tab=readme-ov-file"
