# Stock market prediction model (using Prophet) deployed with FastAPI

To use, query the API with a request similar to the following one,

$ curl \
  --header "Content-Type: application/json" \
  --request POST \
  --data '{"ticker":"MSFT"}' \
  https://mighty-inlet-35813.herokuapp.com/predict


where ticker's value being the company for which you want to have a stock prediction.