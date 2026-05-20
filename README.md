<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=190&section=header&text=Kim%20Ayoung&fontSize=52&fontAlignY=36&desc=3D%20Artist%20·%20Animator%20·%20Technical%20Artist&descAlignY=58&fontColor=ffffff" />

<br/>

[![Email](https://img.shields.io/badge/Email-gdhsf3703%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gdhsf3703@gmail.com)
[![Projects](https://img.shields.io/badge/Portfolio-Projects-111111?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/1bbe3b6a2b2e800fb156f1f39516c772)
[![Arts](https://img.shields.io/badge/Portfolio-Arts-111111?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/321e3b6a2b2e8036ba2fedc3c54c4ded)

<br/>

### 누군가의 상상을 현실로 만드는 아티스트

**캐릭터를 살아있게 만드는 것**을 목표로  
3D 캐릭터 아트, 애니메이션, 리깅, 그리고 셰이더 표현을 공부하고 있습니다.

</div>

---

## About Me

```txt
Name        Kim Ayoung
Role        3D Artist / Animator / Technical Artist
Focus       Character Modeling · Rigging · Animation · Shader
Goal        감정과 생동감이 느껴지는 캐릭터를 만드는 아티스트
```

- 캐릭터 콘셉트부터 모델링, 리깅, 애니메이션까지의 제작 흐름에 관심이 많습니다.
- Unity 환경에서 아트 리소스를 실제 게임 안에 자연스럽게 적용하는 과정을 좋아합니다.
- 셰이더와 기술 아트를 통해 더 설득력 있는 비주얼 표현을 연구하고 있습니다.

---

## Tech Stack

<div align="center">

### Main

![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-111111?style=for-the-badge&logo=unity&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Learning

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white)
![Spine](https://img.shields.io/badge/Spine-FF4000?style=for-the-badge&logoColor=white)

### Technical Art

![HLSL](https://img.shields.io/badge/HLSL-Custom%20Shader-5C2D91?style=for-the-badge)
![GLSL](https://img.shields.io/badge/GLSL-Learning-4CAF50?style=for-the-badge)
![Shader](https://img.shields.io/badge/Shader-Visual%20Expression-00A6ED?style=for-the-badge)

</div>

---

## Projects & Awards

| Year | Project | Result | Role |
|---|---|---|---|
| 2025 | [OverClocking](https://www.notion.so/2025-2-OverClocking-264e3b6a2b2e802e8c8cfa4318d66522) | 2nd Place | Character Concept · Modeling · Rigging |
| 2025 | [별주부전](https://www.notion.so/2025-264e3b6a2b2e805690eeed131a3a28ae) | Game Jam 2nd Place | Spine 2D Animation |
| 2025 | [깽구리](https://www.notion.so/2025-1-264e3b6a2b2e80758d8bfc5409432096) | Project | 3D Character Artist |
| 2024 | [My Summer MATHTAURANT](https://www.notion.so/2-My-Summer-MATHTAURANT-1bbe3b6a2b2e817eb7f5ef4dfb386b96) | Contest 2nd Place | Overall Art |
| 2024 | [DoorBreaker](https://www.notion.so/2024-1-3-DoorBreaker-264e3b6a2b2e80a2bb0beb4a8b044bdf) | Club 3rd Place | Art |

---

## Technical Highlight

### Custom HLSL Shader

> `ship` 프로젝트에서 직접 설계하고 구현한  
> **Selective Color + Radial Mask Shader**

```hlsl
// RGB to HSV 변환 후 색상 범위 판별
float3 hsv = RGBtoHSV(c.rgb);

// 화면 끝까지 정규화한 방사형 마스크
float normDist = dist / maxDist;
float radialMask = lerp(normalMask, invertedMask, saturate(_InvertRadial));

// 선택한 색상만 유지하고 나머지는 그레이스케일 처리
float keep = keepColor ? radialMask : 0.0;
float3 outColor = lerp(grayCol, c.rgb, keep);
```

특정 색상만 선택적으로 강조하고, 화면 중심 또는 외곽 기준으로 색이 사라지는 연출을  
렌더링 로직 수준에서 직접 구현했습니다.

---

## Activities

| Activity | Description |
|---|---|
| NGC Leader, 2025 | 1학년 프로젝트 멘토링 · [관련 영상](https://youtube.com/playlist?list=PLw4Z_hbNrVu4xb1eeeP6DtkNfa-iOamb0) |
| 경기게임마이스터고 학과체험 도우미, 2025 | 게임 개발 학과 체험 보조 |
| Wee클래스 또래상담부 | 또래 상담 활동 |

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

### Contact

**캐릭터 아트, 애니메이션, 기술 아트를 통해  
더 살아있는 게임 경험을 만들고 싶습니다.**

<br/>

[![Email](https://img.shields.io/badge/Contact-gdhsf3703%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gdhsf3703@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=110&section=footer" />

</div>
