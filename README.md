<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=180&section=header&text=Kim%20Ayoung&fontSize=48&fontAlignY=36&desc=3D%20Artist%20·%20Animator%20·%20Technical%20Artist&descAlignY=58&fontColor=fff" />

<br/>

[![Email](https://img.shields.io/badge/gdhsf3703%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gdhsf3703@gmail.com)
[![Portfolio](https://img.shields.io/badge/Projects-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/1bbe3b6a2b2e800fb156f1f39516c772)
[![Arts](https://img.shields.io/badge/Arts-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/321e3b6a2b2e8036ba2fedc3c54c4ded)

<br/>

> 누군가의 상상을 현실로 만드는 아티스트 — **캐릭터를 살아있게 만드는 것**이 목표입니다.

</div>

---

## 🛠 Tech Stack

<div align="center">

**주력**

![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**학습 중**

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white)

**Shader**

![HLSL](https://img.shields.io/badge/HLSL-Custom%20Shader-5C2D91?style=for-the-badge)
![GLSL](https://img.shields.io/badge/GLSL-Learning-4CAF50?style=for-the-badge)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true" />
</div>

---

## 🏆 Projects & Awards

| 연도 | 프로젝트 | 결과 | 역할 |
|------|----------|------|------|
| 2025 | [OverClocking](https://www.notion.so/2025-2-OverClocking-264e3b6a2b2e802e8c8cfa4318d66522) | 🥈 2등 | 캐릭터 아트 콘셉트 · 모델링 · 리깅 |
| 2025 | [별주부전](https://www.notion.so/2025-264e3b6a2b2e805690eeed131a3a28ae) | 🥈 게임잼 2등 | Spine 2D 애니메이션 |
| 2025 | [깽구리](https://www.notion.so/2025-1-264e3b6a2b2e80758d8bfc5409432096) | 프로젝트 | 3D 캐릭터 전담 |
| 2024 | [My Summer MATHTAURANT](https://www.notion.so/2-My-Summer-MATHTAURANT-1bbe3b6a2b2e817eb7f5ef4dfb386b96) | 🥈 공모전 2등 | 아트 전반 |
| 2024 | [DoorBreaker](https://www.notion.so/2024-1-3-DoorBreaker-264e3b6a2b2e80a2bb0beb4a8b044bdf) | 🥉 동아리 3등 | 아트 |

---

## ✨ Technical Highlight — Custom HLSL Shader

> `ship` 프로젝트에서 직접 설계·구현한 **Selective Color + Radial Mask** 쉐이더

```hlsl
// RGB → HSV 변환 후 색상 범위 판별
float3 hsv = RGBtoHSV(c.rgb);

// 화면 끝까지 정규화한 방사형 마스크
float normDist = dist / maxDist;
float radialMask = lerp(normalMask, invertedMask, saturate(_InvertRadial));

// 선택한 색상만 살리고 나머지는 그레이스케일로
float keep = keepColor ? radialMask : 0.0;
float3 outColor = lerp(grayCol, c.rgb, keep);
```

특정 색상만 선택적으로 살리는 연출을 렌더링 로직 수준에서 직접 풀어낸 경험.

---

## 🎬 활동 & 멘토링

- 🏫 **NGC 기장** (2025) — 1학년 프로젝트 멘토링 · [관련 영상](https://youtube.com/playlist?list=PLw4Z_hbNrVu4xb1eeeP6DtkNfa-iOamb0)
- 🎮 경기게임마이스터고 학과체험 도우미 (2025)
- 📖 Wee클래스 또래상담부

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer" />
</div>
