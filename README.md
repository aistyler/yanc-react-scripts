# yanc-react-scripts

```@yanc/react-scripts@git+https://github.com/aistyler/yanc-react-scripts.git#semver:~4.0.0```

## Usage

- create app uaing create-react-app

```sh
$> npx create-react-app \  # cra cli
    cra-app \             # package name
    --scripts-version \    # custom script package
        @yanc/react-scripts@git+https://github.com/aistyler/yanc-react-scripts.git#semver:~4.0.0
```

- edit src/react-app-env.d.ts

```diff
- /// <reference types="react-scripts" />
+ /// <reference types="@yanc/react-scripts" />
```
