# Setting up Development Environment
In the StackBlitz Terminal, execute the following commands:

```
cd angular-excercise && npm i
```

Afterwards, you can utilize the *'npm run ng'* command to execute Angular CLI operations. For instance:
```
npm run ng -- g component test
```
# AngularExcercise

Utilize the provided API to fetch products and exhibit them in a tabular format:
```
https://dummyjson.com/products
```

The parameters available for sending to this API are:
- skip: number
- limit: number

Tasks to be performed:
- The table should exhibit 5 items at a time.
- Incorporate a paginator to facilitate the display of the subsequent 5 items or the retrieval of the preceding items.
