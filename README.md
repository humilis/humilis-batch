# Humilis plug-in to deploy AWS Batch resources

A [humilis][humilis] plug-in layer that deploys all the AWS Batch resources necessary to build a fully operational batch computing system in the AWS cloud.

[humilis]: https://github.com/humilis/humilis


## Installation


```
pip install humilis-batch
```


To install the development version:

```
pip install git+https://github.com/humilis/humilis-batch
```


## Development

Assuming you have [virtualenv][venv] installed:

[venv]: https://virtualenv.readthedocs.org/en/latest/

```
make develop
```

Configure humilis:

```
make configure
```


## Testing

You can test the deployment with:

```
make test
```

If the tests break, you can make sure you are not leaving any infrastructure
behind with:

```bash
make delete
```


## More information

See [humilis][humilis] documentation.

[humilis]: https://github.com/humilis/blob/master/README.md


## Contact

If you have questions, bug reports, suggestions, etc. please create an issue on
the [GitHub project page][github].

[github]: http://github.com/humilis/humilis-batch


## License

This software is licensed under the [MIT license][mit].

[mit]: http://en.wikipedia.org/wiki/MIT_License

See [License file][LICENSE].

[LICENSE]: ./LICENSE.txt


© 2020 German Gomez-Herrero, [FindHotel][fh] and others.

[fh]: http://company.findhotel.net
