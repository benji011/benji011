# [Benjamin Lo](https://benjaminlo.io/) &middot; [![CircleCI Status](https://circleci.com/gh/facebook/react.svg?style=shield&circle-token=:circle-token)](https://app.circleci.com/pipelines/github/benji011/benjaminlo.io) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://benjaminlo.io)

### Benjamin Lo
Benjamin Lo is a qualified Software Engineer currently working on [USERGRAM](https://benjaminlo.io/project/portfolio/ug/) at [bebit, Inc](github.com/bebit).

### GET Basic profile request

Invoking the `get_profile(..)` function calls the API endpoint `https://benjamin_lo.io/api/profile/6195689/` in the background.

```python3
import benjamin_lo
# ...
benjamin_lo.get_profile()
```

Sample response as JSON

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
Invoking the `get_experience(..)` function calls the API endpoint `https://benjamin_lo.io/api/profile/6195689/technologies/` in the background.

```python3
import benjamin_lo
# ...
benjamin_lo.get_experience()
```
Sample response as JSON
```json
"technologies": {
    "frontend": ["React.JS", "Vue.JS"],
    "backend": ["Django", "Laravel", "Zend Framework 1 & 2", "Ruby On Rails"],
    "devops": ["docker", "kubernetes", "Amazon Web Services"]
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
