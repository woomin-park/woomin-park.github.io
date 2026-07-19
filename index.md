<style>
  /* 기본적으로 PC 화면에서는 이 모바일 전용 CV 버튼을 숨깁니다 */
  .mobile-only-cv {
    display: none;
  }

  /* 모바일 화면(화면 너비 768px 이하)에서만 작동하는 규칙 */
  @media (max-width: 768px) {
    /* 1. 원래 있던 햄버거 버튼 영역에 자리를 마련합니다 */
    .site-nav {
      display: flex !important;
      align-items: center;
      gap: 12px;
    }
    
    /* 2. 햄버거 버튼 왼쪽에 배치할 모바일 CV 버튼 디자인 */
    .mobile-only-cv {
      display: inline-block !important;
      font-size: 16px;
      font-weight: 500;
      color: #424242; /* minima 테마 기본 글자 색상 */
      text-decoration: none;
      padding: 4px 8px;
      border: 1px solid #e8e8e8; /* 과하지 않고 정갈한 테두리 */
      border-radius: 4px;
      background-color: #fafafa;
    }
  }
</style>

<!-- 모바일 전용 CV 바로가기 버튼 -->
<script>
  // 이 코드가 테마 구조상 햄버거 버튼 바로 앞으로 가도록 동적으로 위치를 잡아줍니다.
  document.addEventListener("DOMContentLoaded", function() {
    var menuIcon = document.querySelector(".site-nav .menu-icon");
    var cvLink = document.getElementById("mobileCV");
    if (menuIcon && cvLink) {
      menuIcon.parentNode.insertBefore(cvLink, menuIcon);
    }
  });
</script>
<a href="/cv" id="mobileCV" class="mobile-only-cv">CV</a>

<div style="display: flex; align-items: center; gap: 40px; margin-bottom: 20px; flex-wrap: wrap;">

  <div style="flex-shrink: 0;">
    <img src="/profile.jpg" alt="Woomin Park" style="width: 220px; border-radius: 5%; box-shadow: 0 4px 8px rgba(0,0,0,0.05);">
  </div>

  <div style="flex: 1; min-width: 300px;">
    <p style="margin-top: 0;">
      I am Woomin Park (pronounced [pag-u-min] in Korean), <a href="https://www.cla.purdue.edu/directory/profiles/woomin-park.html">a Ph.D. student in the Department of Philosophy at Purdue University</a>. My research sits at the intersection of metaphysics, epistemology, and the philosophy of science.
    </p>
    <p style="margin-bottom: 0;">
      My earlier work in the metaphysics of science explored the possibility of unifying metaphysical grounding and causation, specifically defending causal and grounding contingentism against the challenges posed by grounding necessitarianism. Building on this, I am writing a paper that examines the mutual tensions between Anti-Humean indeterministic law-instance explanations, grounding necessitarianism, and explanatory realism, assessing which of these metaphysical commitments should be retained or revised. 
    </p>
  </div>

</div>

My current epistemological projects explore the normative dimensions of inquiry and the foundations of _epistemic psychology_. The prevailing view often dismisses the _epistemic normativity_ of inquiry on the grounds that inquiry is an action rather than a belief. Against this, I believe that the domain of epistemic normativity validly extends beyond beliefs, and the normativity of inquiry is a _hybrid_ one, combining instrumental and epistemic dimensions. Furthermore, I propose that just as moral psychology is foundational to ethics, epistemic psychology is vital for epistemology. As this field remains largely unexplored, my work aims to lay its groundwork by investigating the distinction between epistemic and conventional norms. By comparing it to the well-known moral/conventional distinction, I believe that a robust epistemic/conventional distinction is meaningful and essential for undertaking epistemic psychology.

Before pursuing philosophy, I trained to be a physics teacher at [Korea National University of Education](https://www.knue.ac.kr/phys/). Then I earned a B.A. in philosophy from [Yonsei University](https://philosophy.yonsei.ac.kr) and an M.A. in philosophy from [Seoul National University](https://philosophy.snu.ac.kr). Following my master's degree, I was a teaching associate of humanities at [Pohang University of Science and Technology (POSTECH)](https://hss.postech.ac.kr) during the pandemic. Before coming to Purdue, I was a doctoral student in philosophy at [Seoul National University](https://philosophy.snu.ac.kr). I have spent my life navigating the contrast between the stifling competition of a megacity and the relative tranquility of mid-sized urban environments. I was born in Seoul and raised in Incheon, South Korea. Then, I lived four years in Cheongju for my first undergraduate studies, followed by seven and a half years commuting between Incheon and Seoul. After spending a year in Pohang and two years in Tallahassee, Florida, I am now in my second year at Purdue. Although I am drawn to the aesthetic of minimalism in music, architecture, and industrial design, my own outputs tend toward the maximalist.
