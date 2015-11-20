PyTest Mirror
=============

Mirror of PyTest package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prospector: see http://pytest.org/latest


### Using prospector with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/blarghmatey/pytest-mirror
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pytest
