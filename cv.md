---
layout: page
title: Curriculum Vitae
permalink: /cv/
---

<style>
  /* 기본 설정 */
  .mobile-pdf-notice { display: none; }
  .mobile-pdf-preview { display: none; }
  .desktop-pdf-viewer { display: block; }
  
  /* 화면 너비가 768px 이하(모바일 기기)일 때 작동하는 규칙 */
  @media (max-width: 768px) {
    .desktop-pdf-viewer { display: none; } /* 데스크톱용 긴 뷰어 숨김 */
    .mobile-pdf-notice { display: block; }  /* 모바일 안내문 표시 */
    .mobile-pdf-preview { 
      display: block; 
      width: 100%;
      height: 450px; /* 모바일 화면에서 첫 페이지만 예쁘게 담기는 최적의 높이 */
      overflow: hidden; /* 스크롤이 꼬이지 않도록 내부 스크롤 차단 */
      border: 1px solid #e8e8e8;
      border-radius: 6px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05); /* 액자 같은 은은한 그림자 효과 */
    }
  }
</style>

<!-- 새 탭 열기 버튼 -->
<div style="margin-bottom: 20px; text-align: right;">
  <a href="/Woomin_Park_CV.pdf" target="_blank" rel="noopener noreferrer" style="display: inline-block; padding: 8px 16px; border: 1px solid #ccc; color: #555; text-decoration: none; font-size: 0.9em; border-radius: 4px; font-weight: 500;">
    📄 Open CV in New Tab
  </a>
</div>

<!-- 모바일용 안내문 -->
<div class="mobile-pdf-notice" style="background-color: #f8f9fa; padding: 15px; text-align: center; border-radius: 6px; margin-bottom: 15px; border: 1px solid #eee;">
  <p style="margin: 0; color: #666; font-size: 0.9em; line-height: 1.5;">
    The PDF viewer may not scroll correctly on mobile screens.<br>
    Please use the <strong>Open CV in New Tab</strong> button above to read the full document.
  </p>
</div>

<!-- 모바일 전용 PDF 첫 페이지 미리보기 구역 -->
<div class="mobile-pdf-preview">
  <object data="/Woomin_Park_CV.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="100%" height="100%">
    <p>Your browser does not support embedding PDFs.</p>
  </object>
</div>

<!-- 데스크톱 전용 전체 PDF 뷰어 구역 -->
<div class="desktop-pdf-viewer">
  <object data="/Woomin_Park_CV.pdf" type="application/pdf" width="100%" height="1000px" style="border: 1px solid #eee; border-radius: 4px;">
    <p>Your browser does not support embedding PDFs. Please use the button above to view the CV.</p>
  </object>
</div>
