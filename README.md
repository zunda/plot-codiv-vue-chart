# covid-vue-chart
Vue application to plot time series from COVID-19 cases

## Project setup
```
yarn install
```

### Fetches and formats data to be plotted
Creates 'src/assets/regions.json', 'src/assets/timeSeries.json', and `src/assets/timestamps.json`:

```
yarn fetchdata
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
The command also triggers `yarn fetchdata` to refresh the data.

```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## License
### The app code
Copyright 2020 by zunda, under [MIT License](LICENSE.txt).

### Favicon
https://fontawesome.com/icons/clinic-medical

Copyright by Fonticons, Inc., under [CC BY 4.0 License](https://fontawesome.com/license/free).
