# adobe-cs6-patcher
A private patcher for adobe cs6. This is not to be used for illegal activity... it only exists because Adobe stopped supporting the CS6 activation process for those who legitimately purchased and own that product... which is evil.

## Getting Started

This a rust based patch that is meant only for the patching of adobe CS6 products. This project includes and compiles the two patch files needed. As this is a rust project, you will need cargo and this patch only runs on the windows version of this application. 

### Prerequisites

What things you need to install the software and how to install them

To build this patcher from source code run the following command. 

```
cargo build --release
```

Each of these arguments does the following.

cargo: The rust package manager.
build: build the binary for this software. 
--release: A binary optimized version


### Installing

This patcher does not actually keep anything on the system long term other than the patched file. 

However make sure that you either change the glob to search the right drive or use the standard C drive.

## Running the tests

This application has very little code. Roughly 70 lines. 
So there is a single unit test, however that unit test is the standard 2+2=4.

cargo test 

### Coding style

This project follows all rust standards and should compile without any warnings. 
If not, bad Xander~! Go fix it. 

## Deployment

When running the compiled binary, make sure to run it as Administrator mode in windows. 

If you forget, nothing terrible will happen, it will just fail when trying to remove the old file. 

Under those circumstances, a reinstall will not be needed. Just run the patcher again.

## Built With

* [Rust 1.92.0 (ded5c06cf 2025-12-08)](https://www.rust-lang.org/en-US/) - Language Used
* [Glob 0.3](https://github.com/rust-lang-nursery/glob) - Used for finding all the files that need patched
* [blake 0.10.6](https://blake2.net/) - Used for the hashing technology
* [digest "0.10.7"](https://docs.rs/digest/0.7.2/digest/) - Used for converting file object to hash 
## Contributing

Please read [CONTRIBUTING.md](https://github.com/recursiverighthook/adobe-cs6-patcher/graphs/contributors) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/recursiverighthook/adobe-cs6-patcher/tags). 

## Authors

* **Alexander Montgomery** - *Initial work* - [recursiverighthook](https://github.com/recursiverighthook/adobe-cs6-patcher)
* **PrudentDev, LLC** Updated for latest Rust stuff
See also the list of [contributors](https://github.com/recursiverighthook/adobe-cs6-patcher/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
