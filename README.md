Until [.env files doesn't supported by docker deploy](https://github.com/moby/moby/issues/29133) we need to load environment variables manually, like this:

`export $(cat secrets/*.env)`