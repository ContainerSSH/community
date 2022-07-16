# Examples and test auth-config server should be exempt from the Apache-2.0 license.

We recently decided that ContainerSSH should be released under the Apache-2.0 license. However, the [examples](https://github.com/containerssh/examples) and the [test-auth-config server](https://github.com/ContainerSSH/libcontainerssh/tree/main/cmd/containerssh-testauthconfigserver) should not fall under this license and should remain "free to copy-paste" under the MIT-0 or the Unlicense so people can integrate it into their setups without needing to copy the license file.

Arguably, these parts of the codebase could also fall under the [merger doctrine](https://en.wikipedia.org/wiki/Idea%E2%80%93expression_distinction#Merger_doctrine), which makes them uncopyrightable anyway.

## Benefits

- Free to copy-paste (people will do it anyway)
- Legal certainty

## Drawbacks

- Non-uniform licensing
