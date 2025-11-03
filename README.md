# Gopp
zdxasw erwefsedf
curl https://data.gopher-ai.com/api/v1/search/live \
  -H "Authorization: Bearer iGUJpZvMHCpOLsjSIos9Y4jwpIRZFAIBSlVUONUr34Vhh7Pt" \
  -X POST \
  -H "Content-Type: application/json" \
  -d '{
    "type": "twitter",
    "arguments": {
      "type": "searchbyquery",
      "query": "from:gopher_ai",
      "max_results": 100
    }
  }'
