# project

[tool.ruff]
select = ["I"]
fix = true
line-length = 88

[tool.ruff.isort]
force-single-line = true
 from mypackage.subpackage2 import (  # long comment that seems to be a problem
    a_long_variable_name_that_causes_problems,
    item2,
)
