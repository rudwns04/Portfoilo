# 📝 이경준 취업 포트폴리오

딥러닝 AI 엔지니어 신입으로 Python, Linux, TensorFlow, C++, OpenCV, GitHub 및 Raspberry Pi와 같은 다양한 기술을 보유하고 있습니다.  프로그래밍 능력을 바탕으로 열정적으로 문제 해결과 혁신적인 솔루션을 개발하는 데 탁월한 역량을 발휘할 수 있습니다. 신선한 시각과 열정으로 최신 기술 동향을 주도적으로 습득하고 적용할 자신이 있습니다. 🤗

  <br />
  
### 사용된 기술
Python, Linux, TensorFlow, C++, OpenCV, Git, Raspberry Pi
  
  <br />

  "activity": [
    {
      "id": 0,
      "name": "첫번째 활동",
      "period": ["2022. 06", "2022. 08"],
      "description": "첫번째 활동에 대한\n 간략한 설명"
    },
    {
      "id": 1,
      "name": "두번째 활동",
      "period": ["2022. 06", "2022. 08"],
      "description": "두번째 활동에 대한 간략한 설명"
    }
  ],

```

<br />
<br />
<br />
<br />

## education

<img width="960" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/2ddbd623-21f9-4521-8d11-05e6353726d1">

전공, 부트캠프, 각종 교육에 대해 적어주세요.<br />
간략한 설명을 적는 `description`은 `\n`으로 줄바꿈이 가능합니다.<br />
위의 [activity](#activity)와 동일한 구성이라 넘어갑니다~ 휘리릭~ 😇


> 대충 더이상의 자세한 설명은 생략한다 짤

```json

  "education": [
    {
      "id": 0,
      "name": "첫번째 교육",
      "period": ["2013. 02", "2020. 02"],
      "description": "첫번째 교육에\n 대한 간략한 설명"
    },
    {
      "id": 1,
      "name": "두번째 교육",
      "period": ["2013. 02", "2020. 02"],
      "description": "두번째 교육에 대한 간략한 설명"
    }
  ],

```

<br />
<br />
<br />
<br />

## certificate


<img width="960" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/24b49321-9a49-4ff9-9e8b-366a2893aeb7">

각종 자격 증명에 대해 적어주세요. 자격 시험의 주관처도 입력해주세요.<br />
여기도 위와 거의 동일한 구성이라... 하핫... 😅


```json

  "certificate": [
    {
      "id": 0,
      "name": "TOEIC 1000점",
      "date": "2019. 07. 28",
      "organizer": "ETS" // 주관처를 적어주세요.
    },
    {
      "id": 1,
      "name": "OPIC IH",
      "date": "2019. 07. 28",
      "organizer": "ETS"
    }
  ]

```


<br />
<br />
<br />
<br />

## COLOR 변경하기

**🚨 반드시 컬러를 변경해주세요 🚨**


여러 사람이 너무나도 똑같은 디자인의 포트폴리오를 사용하게 된다면 그것도 문제겠죠?😉<br />
`tailwind` 의 `theme` 를 사용하여 편하게 컬러를 커스텀할 수 있도록 해두었으니 **꼭 변경해서 사용해주세요!**


프로젝트 루트 경로의 `/tailwind.config.js` 를 수정해주세요.<br />
검정, 흰색 계통의 모노톤은 폰트 컬러, 가로선, 배경색 등에 사용되고 있습니다. 굳이 변경하지 않아도 괜찮아요.<br />
`PRIMARY_LIGHT` `PRIMARY` `PRIMARY_HEAVY` `GRADIENT_FROM` `GRADIENT_TO` 5가지 색만 변경해주세요!

```js

...
theme: {
    extend: {
      // NOTE: 본 템플릿은 대부분이 모노톤으로 이루어져 있습니다. primary 컬러만 수정하여 사용하시는 것을 권장드립니다.
      colors: {
        GRAY_LIGHT: "#f1f3f5",
        GRAY: "#adb5bd",
        GRAY_HEAVY: "#868e96",
        GRAY_EXTRAHEAVY: "#495057",
        BLACK: "#212529",
        /**
         * @description selection(드래그 블록)에 사용되는 컬러입니다.
         */
        PRIMARY_LIGHT: "#c3fae8",

        /**
         * @description 자기소개의 이름 부분, code tag의 darkmode에 사용되는 컬러입니다.
         */
        PRIMARY: "#12b886",

        /**
         * @description code tag, link hover icon에 사용되는 컬러입니다.
         */
        PRIMARY_HEAVY: "#087f5b",

        /**
         * @description 페이지 최상단 gradient의 시작 컬러입니다.
         */
        GRADIENT_FROM: "#51cf66",

        /**
         * @description 페이지 최상단 gradient의 종료 컬러입니다.
         */
        GRADIENT_TO: "#0c8599",
      },
    },
  },

```

나는 어떤 색 조합이 좋은지 모르겠다! 고민이신 분들은 마음에 드는 메인 컬러 하나만 정하신 후, [어도비 컬러](https://color.adobe.com/ko/create/color-wheel) 에서 `유사` `음영` 으로 어울리는 색을 찾아보셔도 좋을 것 같아요😉
혹은, [어도비 컬러의 탐색 탭](https://color.adobe.com/ko/explore)에서 인사이트를 얻어보셔도 좋겠습니다.🌈

<br />
<br />
<br />
<br />

## SEO

이제 SEO를 향상시켜 볼까요?<br />
`very simple portfolio` 는 편한 SEO 설정을 위해 `next-seo` 를 설치해두었어요.


`/src/pages/_app.tsx` 경로의 `DEFAULT_SEO` 만 수정해주시면 됩니다!
각 옵션에 대한 정보는 [next-seo 문서](https://github.com/garmeeh/next-seo#nextseo-options)를 참고하세요!

```js


/**
 * @description SEO를 위해 본인의 정보로 수정해주세요.
 */
const DEFAULT_SEO = {
  title: "홍길동 | Front-End Dev",
  description: "안녕하세요, 프론트엔드 개발자 홍길동입니다.",
  canonical: "https://www.naver.com/",
  openGraph: {
    type: "website",
    locale: "ko_KR",
    url: "https://www.naver.com/",
    title: "홍길동 | Front-End Dev",
    site_name: "홍길동 | Front-End Dev",
    images: [
      {
        url: "/share.png", // 카카오톡을 비롯한 공유용 이미지 경로 public/share.png에 원하는 이미지를 저장해주세요.
        width: 285,
        height: 167,
        alt: "홍길동 | Front-End Dev",
      },
    ],
  },
  additionalLinkTags: [
    {
      rel: "icon",
      href: "/favicon.ico",
    },
  ],
  additionalMetaTags: [
    {
      name: "application-name",
      content: "홍길동 | Front-End Dev",
    },
    {
      name: "msapplication-tooltip",
      content: "홍길동 | Front-End Dev",
    },
    {
      name: "viewport",
      content: "width=device-width, initial-scale=1",
    },
  ],
};

```





잊지말고 favicon도 설정해주세요! (탭의 조그마한 아이콘)<br />
`/public/favicon.ico` 경로에 ico 파일을 저장해주세요.<br />
원하는 이미지를 favicon으로 변환해주는 [realfavicongenerator](https://realfavicongenerator.net/)를 사용해보셔도 좋을 것 같아요.

![image](https://github.com/sjoleee/very-simple-portfolio/assets/82137004/a6341417-6ecb-4149-8c7a-8122bcfe6f23)

<br />
<br />
<br />
<br />

## Vercel 배포하기


Vercel은 클릭 몇 번으로 아주아주 편하게 프로젝트를 배포할 수 있는 배포, 호스팅 서비스에요.<br />
https://vercel.com/new 에서 github으로 로그인하신 후, 포트폴리오 레포지토리를 선택하여 배포해주시면 됩니다!

> 너무 편하다...!



<img width="1256" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/f0ab905d-5e62-4970-a681-dfa761781df9">



<br />
<br />
<br />
<br />

## Google Analytics

포트폴리오에 방문자가 몇명인지 궁금하지 않으셨나요?🕵️‍♀️<br />
간단한 GA 설정만으로 데이터 수집이 가능합니다!

<br />
<br />

**Step 1️⃣ Google Analytics에 가입해주세요.**

https://analytics.google.com/ 에 방문하여 가입을 진행해주세요.<br />
간단한 정보를 입력하고, 플랫폼을 웹으로 선택해주시면 아래와 같은 화면이 나옵니다.<br />

<img width="997" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/af2ee54f-583f-427e-b24b-ad108cedbc8e">

<br />

여기의 Vercel로 배포한 우리 포트폴리오의 url을 작성해줍니다.<br />
그럼 아래와 같이 `G-` 로 시작하는 **측정 ID** 를 제공해줄거에요.

<img width="399" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/39d2e158-f018-4d0d-8d1b-d17596de6c05">


<br />
<br />

**- Step 2️⃣ 코드를 작성합니다.**

프로젝트 루트 경로에 `/.env` 파일을 만들고 아래와 같이 작성해주세요. <br />
측정 ID를 환경변수로 사용하고, 외부로 노출되지 않도록 합니다. (gitignore는 이미 작성해두었어요!)

```

NEXT_PUBLIC_GOOGLE_ANALYTICS = 'G-0000000000' // 아까 받은 측정 ID를 입력해주세요.

```

<br />

이제, `/src/lib/gtag.ts` 폴더와 파일을 생성하고 아래와 같이 작성해주세요.<br />
GA에서 제공하는 태그입니다. 이 경우에는 페이지가 보여지면 집계될 수 있도록 하는 `pageview` 함수가 작성되어 있습니다.<br />
아마 에러가 발생할텐데, 계속해서 진행하시면 해결됩니다!

```js

const GA_TRACKING_ID = process.env.NEXT_PUBLIC_GOOGLE_ANALYTICS;

export const pageview = (url: URL) => {
  window.gtag("config", GA_TRACKING_ID, {
    page_path: url,
  });
};

interface GTagEvent {
  action: string;
  category?: string;
  label?: string;
  value?: string;
}

export const event = ({ action, category, label, value }: GTagEvent) => {
  window.gtag("event", action, {
    event_category: category,
    event_label: label,
    value: value,
  });
};


```

<br />

루트 경로에 `/environment.d.ts` 파일을 만들고 아래와 같이 작성해주세요.

```ts

namespace NodeJS {
  interface ProcessEnv extends NodeJS.ProcessEnv {
    NEXT_PUBLIC_GOOGLE_ANALYTICS: string;
  }
}

```

<br />

타입스크립트 환경이므로 gtag의 타입을 설치해줍니다. > 제가 이미 설치해두었어요 😉

```
yarn add -D @types/gtag.js
```
or
```
npm install @types/gtag.js --dev
```

<br />

`/src/pages/_app.tsx` 에 다음과 같은 코드를 추가합니다.

```js

import * as gtag from "../lib/gtag";
const GA_TRACKING_ID = process.env.NEXT_PUBLIC_GOOGLE_ANALYTICS;

const App = ({ Component, pageProps }: AppProps) => {
  const router = useRouter();

  useEffect(() => {
    const handleRouteChange = (url: URL) => {
      gtag.pageview(url);
    };
    router.events.on("routeChangeComplete", handleRouteChange);
    router.events.on("hashChangeComplete", handleRouteChange);
    return () => {
      router.events.off("routeChangeComplete", handleRouteChange);
      router.events.off("hashChangeComplete", handleRouteChange);
    };
  }, [router.events]);

  return (
    <>
      {/* Global Site Tag (gtag.js) - Google Analytics */}
      <Script
        strategy="afterInteractive"
        src={`https://www.googletagmanager.com/gtag/js?id=${GA_TRACKING_ID}`}
      />
      <Script
        id="gtag-init"
        strategy="afterInteractive"
        dangerouslySetInnerHTML={{
          __html: `
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', '${GA_TRACKING_ID}', {
          page_path: window.location.pathname,
        });
      `,
        }}
      />
      <DefaultSeo {...DEFAULT_SEO} />
      
      ... 후략

```



<br />
<br />

**- Step 3️⃣ Vercel에서 환경변수를 등록해주세요.**

아까 `.env`로 환경변수를 등록했지만, vercel에 따로 등록해주어야해요. (.env는 gitignore로 인해 깃에 포함되지 않아요)<br />
vercel에서 포트폴리오 프로젝트의 설정으로 들어간 다음, 아래 사진처럼 환경변수를 등록해주세요.

<img width="1260" alt="image" src="https://github.com/sjoleee/very-simple-portfolio/assets/82137004/1dac46fe-9028-4d29-aa60-55ce424e2539">


<br />
<br />

**- Step 4️⃣ GA 데이터 수집을 기다려주세요.**

GA가 열심히 데이터를 수집하여 며칠내로 데이터 조회가 가능해질거에요.<br />
https://analytics.google.com/ 에서 페이지 방문과 실시간 방문자를 볼 수 있게 될거에요!


그리고, 구글에 포트폴리오가 검색될 수 있도록 [구글 서치콘솔에 URL 색인 생성을 요청](https://support.google.com/webmasters/answer/9012289?hl=ko#request_indexing)하세요!

<br />
<br />

# Done

축하합니다! 포트폴리오를 만드셨군요!
👍👍👍👍👍👍👍👍👍👍👍👍👍👍👍👍


버그나 개선 등의 의견은 언제든 환영입니다!
👍👍👍👍👍👍👍👍👍👍👍👍👍👍👍👍



