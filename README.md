1. add new fields to customer model:
    - demographic: object
    - locale: object
    - interests: array
    - brands: array
    - products: array

2. create a new serializer for each attr above.
3. refactor the updatecustomer command to fetch this data
4. search advanced query in order to allow user filter by this news fields
5. create a new django backend filter to perform getting user by this attributes
6. test!!!

# nvg-cdp-infra
