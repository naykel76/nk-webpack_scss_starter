# NAYKEL webpack scss starter pack

Compile scss to css with vendor prefixes.

``` css
.class {
  user-select: none; 
}

outputs...

.myClass {
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none; 
}
```

## Install dependencies
`npm install`

## Run dev server (local development)
`npm start`

## Build distribution
`npm run build`

## Watch files
`npm run watch`
