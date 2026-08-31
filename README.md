# MODU Firmware

MODU split keyboard용 ZMK 보드, 쉴드 및 기능 모듈 소스입니다.

빌드하려면 `west build`가 동작하는 ZMK 개발 환경과 Zephyr SDK가 필요합니다.

Windows에서는 다음 명령으로 좌·우 BLE 펌웨어를 생성할 수 있습니다.

```bat
build.bat C:\zmk\app
```

생성된 `modu_left.uf2`와 `modu_right.uf2`는 `outputs` 폴더에 저장됩니다.

트랙볼의 외측·내측 설치 방향은 P0.08 상태에 따라 부팅 시 선택됩니다.

미리 빌드된 펌웨어는 GitHub Releases에서 배포합니다.

## License

MODU 소스는 [MIT License](LICENSE)로 배포됩니다. 포함된 외부 코드의 고지는 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)를 참고하세요.
