BOJ Tier
========
문제를 풀면 등급이 올라 공부할 동기를 부여해주는 시스템

### Prerequisites
- Python 3.5+
- pipenv 5.1+

### Instruction
```
# Install dependencies
pipenv install

# Configure
cp settings.default.py settings.py
pipenv run python initialize_data.py

# Run the server
pipenv run python runserver.py
```

### TODOs
- [x] 사찰 기능
- [x] 백업 기능
- [x] 유저 등급 기능
- [x] 문제 난이도 기능
- [x] 유저 순위
- [x] 문제 순위
- [x] Prob API
- [ ] User API
- [ ] Prob UI
- [ ] Ranking UI
- [ ] 유저 페이지 디자인
- [ ] 문제 난이도 확장 프로그램

<br>

--------

*BOJ-tier* is primarily distributed under the terms of the [GNU Affero General
Public License v3.0] or any later version. See [COPYRIGHT] for details.

[GNU Affero General Public License v3.0]: LICENSE
[COPYRIGHT]: COPYRIGHT
