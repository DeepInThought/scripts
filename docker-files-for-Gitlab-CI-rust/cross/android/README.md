Docker images with preinstalled [RUST](https://www.rust-lang.org/) ARMv7 for [ANDROID](https://www.android.com/), [node.js](https://nodejs.org) and [AWS CLI](https://aws.amazon.com/ru/cli/) for [GitLab CI runner](https://gitlab.com/gitlab-org/gitlab-ci-multi-runner).
Usage:
```linux-armv7-android:
      stage: build
      image: parity/rust-android:gitlab-ci
      script:
        - cargo build ...
```
