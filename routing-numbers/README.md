# Routing Numbers

Build a small application that fetches and updates the Federal Reserve's current list of Banks and Routing numbers and then exposes a JSON API where users can lookup a Bank's details by routing number.

## Resources

Bank Data: http://www.fededirectory.frb.org/FedACHdir.txt

Truncated Bank Data: https://gist.github.com/jakehow/3d96b83c4a4a1e6313d4/raw/f2990b4cef86fe9454ba1a643ccee118ca0b5757/truncated_list

 _This is the first 100 lines of the file, much easier to deal with if you are requesting it a lot._

## Example Behavior

`curl http://hostname/banks/123456789`

Output:

```json
{
  name: "First Bank of Zipmark",
  routing_number: "123456789",
  record_type: "Record Type",
  phone_number: "212-555-1212",
  address: {
    street: "56 W 22nd St",
    street_2: "9th Floor",
    city: "New York",
    state: "NY",
    zip_code: "10010"
  }
}
```

## Ideas for Enhancements

* deployable to Heroku
* provide a web client that allows a user to enter a routing number into a form and see the results in a browser
* scheduling/backgrounding/resilience
* track updates and changes

[Source](https://github.com/zipmark/zipmark-code-challenge)
