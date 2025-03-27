# Code Citations

## License: unknown
https://github.com/erwinmareto/FSWD-Week13/tree/96341acfda7640e4bbd2d7c1b02debd399d3e40c/frontend/src/modules/axios.js

```
request.use(
  (config) => {
    const accessToken = localStorage.getItem("token");
    if (accessToken) {
      config.headers.Authorization = `Bearer ${accessToken}`;
    }
    return config;
  },
  (error) => {
    return Promise
```

