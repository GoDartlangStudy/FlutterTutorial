# flutterTutorial

1. https://flutter.dev/docs/get-started/install/macos - flutter sdk 설치 (macOS) <br>
https://miryang.dev/2019/07/10/install-flutter/ (macOS)

2. Android SDK 설치

3. flutter 의존성 확인 (설치완료확인) <br>
```bash
$ flutter doctor
```
3. IDE 에 flutter plugin 설치

4. Flutter project 생성! <br>
```bash
$ flutter create my_app
```

<h6>생성할 때 프로젝트 이름을 모두 소문자로 해야한다. (Underscore 사용)</h6>

```
-- camelCase 로 생성 시 에러..

use `lowercase_with_underscores` for package names.

Package names should be all lowercase, with underscores to separate words,
`just_like_this`.  Use only basic Latin letters and Arabic digits: [a-z0-9_].
Also, make sure the name is a valid Dart identifier -- that it doesn't start
with digits and isn't a reserved word.
```