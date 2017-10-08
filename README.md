### Task

Implement File Converter that is able to convert from **any** to **any** other format. For example:

* `csv` to `json`
* `json` to `xml`

and so on.

As a result of implementation, you need to have a working File Converter ready to be used from as a CLI application.

All tests should pass.

### Installation

Run

```bash
composer install
```

### Usage

To run the converter, execute

```bash
php convert.php test.xml csv test.csv
```

where 

* `test.xml` is the source file we want to convert from
* `csv` is a desired output format
* `test.csv` is a file name we want to convert to

### Unit Tests

To run unit tests, execute

```bash
vendor/bin/phpunit
```