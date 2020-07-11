[![CircleCI Status](https://circleci.com/gh/facebook/react.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/facebook/react)

### Benjamin Lo
A qualified & professional Full Stack Software Engineer currently working on [USERGRAM](https://benjaminlo.io/project/portfolio/ug/) at [bebit, Inc](github.com/bebit). (Not a library you can actually download)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install benjamin_lo
```

Alternatively, if you prefer other other package managers, try:

```bash
npm install benjamin_lo.js
yarn add benjamin_lo.js
bower install benjamin_lo.js
```

### GET Basic profile request
Sample response

```json
"basic_info": {
    "id": 6195689,
    "full_name": "Benjamin Lo",
    "nationality": "British",
    "profession": "Full Stack Engineer",
    "years_of_experience": 6
}
```

## GET Technologies & experience request
Sample response
```json
"technologies": {
    "frontend": ["React.JS", "Vue.JS"],
    "backend": ["Django", "Laravel", "Zend Framework 1 & 2", "Ruby On Rails"],
    "devops": ["docker", "kubernetes", "Amazon Web Services"]
}
```


## Usage

```python3
import benjamin_lo

is_hungry = benjamin_lo.is_hungry()
job_status = benjamin_lo.status()
benji_obj = benjamin_lo.code_my_stuff(msg="I need a qualified developer!!!")
```

Sample output
```bash
>>> True
>>> {"actively_job_hunting": False, "open_to_negotiations": True, "hungry": True}
>>> {"status_code": 200, "response": "Sure let's talk! :)"}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
