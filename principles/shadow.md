# Shadow

## Shadow

그림자는 화면에 깊이감을 제공하여 주요 요소를 돋보이게 만들고 시각적인 계층을 형성하고 콘텐츠의 그루핑을 만든다.

Card, Bar 등에 사용하여 행동을 유도하는데 사용될 수 있다.

## Usage

그림자는 아래 9단계의 높이를 사용한다. UI 요소 사이의 높이를 나타내기 때문에 제품 전반 일관되게 사용해야 한다.

![](../.gitbook/assets/image%20%28164%29.png)

![](../.gitbook/assets/image%20%28144%29.png)

![](../.gitbook/assets/image%20%28154%29.png)

### 

### Shdow 1

높이값 Y 1px로 한다. 로고 리스트 같은 크게 중요하지 않은 요소에 사용한다.

![](../.gitbook/assets/untitled-a51aec2e-43bf-4ec2-a007-9f7b0e69529a.png)

```text
background: #FFFFFF;
box-shadow: 0 1px 4px 0 rgba(0,0,0,0.08);
```

### Shadow 2

높이값 Y 2px로 한다. 풀스크린이 아닌 그리드 형식의 카드에 사용한다.

![](../.gitbook/assets/untitled-1a6bac06-fd6c-4962-8c22-9c521283c00e.png)

```text
background: #FFFFFF;
box-shadow: 0 2px 12px 0 rgba(0,0,0,0.12);
```

### Shadow 3

높이값 Y 4px로 한다. 1단 카드에 사용한다.

![](../.gitbook/assets/untitled-7cfbdafe-830c-4ff1-9d66-985745a08f6a.png)

```text
background: #FFFFFF;
box-shadow: 0 4px 20px 0 rgba(0,0,0,0.12);
```

