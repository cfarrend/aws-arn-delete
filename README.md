[![CircleCI](https://circleci.com/gh/cfarrend/aws-arn-delete.svg?style=svg)](https://circleci.com/gh/cfarrend/aws-arn-delete)

# aws-arn-delete
Ambitious attempt at deleting AWS resources by using Amazon Resource Name (ARN) format

## Installing
:)

## Developing
### Using Batect
This project uses https://github.com/charleskorn/batect as a default method of developing. Batect allows you to develop locally on your development machine without the need of installing all dependencies or setting up a virtual environment yourself. Batect is also integrated into the CI process so you can replicate the same steps done on building

#### Requirements
* Docker 17.06 or newer
* Java 8 or newer
* Mac OS X and Linux: `curl`
* Windows: Windows 10 OS

#### Setting up environment
##### Mac OS / Linux
```
./batect <command>
```

##### Windows
```
.\batect.cmd <command>
```

#### Useful Flags + Commands
```
$ ./batect --help
<help prompt>

$ ./batect --list-tasks
Available tasks:
- development-env
```

### Not using Batect
Feel free to set up your development in your own way, however no support will be given setting up the project as it has been developed using `Batect`, it is also integrated into CI. We suggest to consider using it as it can help to contribute to the shared development environment as a whole, minimal setup is needed
