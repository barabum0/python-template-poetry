> [!TIP]
> I recommend using my new repository template: [python-template-uv](https://github.com/barabum0/python-template-uv). It employs modern and more efficient tools — uv and ruff - instead of poetry and black.

# Template for my Python (non-packages) projects
Feel free to use!

### Before using, rename the project and docker image in following files
- [`pyproject.toml`](pyproject.toml)
- [`docker-compose.yml`](docker-compose.yml)
- [`.github/workflows/build-docker-image-release.yml`](.github/workflows/build-docker-image-release.yml)
  - **and uncomment the `on` section in this file for it to work**
