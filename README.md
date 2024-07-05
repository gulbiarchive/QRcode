# QRcode
🦉 기술 블로그로 바로 이동하는 qrcode 🦉

## Library
`qrcode`, `pillow` 총 2개 필요   
`qrcode`라이브러리는 이미지 처리에 사용되는 `pillow` 라이브러리에 의존하기 때문에 함께 설치

## qrcode, pillow 설치
```
pip install qrcode
pip install pillow
```

### python3 사용 시
```
pip3 install qrcode
pip3 install pillow
```

## make()
- QR code 생성
- 형식 : `qrcode.make(url)`

## save()
- 이미지 파일로 저장
- 형식 : `qrcode저장된변수.save('./파일명.png')`
