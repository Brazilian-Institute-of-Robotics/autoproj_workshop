- A description of the changes proposed in the pull request.

- Use the following settings in the overrides file for docker testing

    ```yaml
      overrides:
      - pkg_set:github:/Brazilian-Institute-of-Robotics/<package_set>.git:
        branch: <branch>
      - <package>:
        github: Brazilian-Institute-of-Robotics/<package>
        branch: <branch>
    ```  
- A short description of the requested feature.

  - What was added/changed in this update

  - A reference to a related issue in your repository.

- Depends On:
    
   - Dependencies on other PRs should be included here
