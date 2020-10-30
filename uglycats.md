require 'open-uri'

url = "https://learn-co-curriculum.github.io/json-sight-example"

uri = URI.parse(url)

response = Net::HTTP.get_response(uri)

response.body