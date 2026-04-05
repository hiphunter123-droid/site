<!doctype html>
<html lang="ko">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crypto Commerce - 코인으로 쇼핑하세요</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', sans-serif;
    }
    .app-wrapper {
      height: 100%;
      width: 100%;
      display: flex;
      flex-direction: column;
      background: #fafafa;
      overflow-y: auto;
    }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body>
  <div class="app-wrapper">
   <!-- Header -->
   <header class="bg-white border-b border-gray-200 sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-8 py-5">
     <div class="flex items-center justify-between">
      <div class="text-2xl font-bold tracking-tight text-gray-900" id="logo-text">
       LOGO
      </div>
      <nav class="hidden md:flex gap-8 absolute left-1/2 transform -translate-x-1/2">
       <a href="#benefits" class="text-gray-700 hover:text-gray-900 transition text-sm font-medium">혜택 안내</a> <a href="#products" class="text-gray-700 hover:text-gray-900 transition text-sm font-medium">상품 보기</a> <a href="#support" class="text-gray-700 hover:text-gray-900 transition text-sm font-medium">고객 지원</a>
      </nav>
      <div class="flex gap-4">
       <button class="text-gray-700 hover:text-gray-900 transition text-sm font-medium border border-gray-300 px-4 py-2 rounded-lg hover:bg-gray-50">로그인</button> <button class="bg-gray-900 text-white hover:bg-gray-800 transition text-sm font-medium px-4 py-2 rounded-lg">회원가입</button>
      </div>
     </div>
    </div>
   </header><!-- Hero Section -->
   <section class="bg-white py-20 px-8">
    <div class="max-w-6xl mx-auto text-center">
     <h1 class="text-5xl md:text-6xl font-bold text-gray-900 mb-4 leading-tight" id="hero-title">코인으로 더 저렴하게 쇼핑하세요!</h1>
     <p class="text-xl text-gray-600 mb-10" id="hero-subtitle">USDT 결제 시 최대 10% 할인</p>
     <div class="flex gap-4 justify-center flex-wrap">
      <button class="bg-gray-900 text-white hover:bg-gray-800 transition font-semibold px-8 py-3 rounded-lg text-lg"> 지금 시작하기 </button> <button class="border-2 border-gray-900 text-gray-900 hover:bg-gray-50 transition font-semibold px-8 py-3 rounded-lg text-lg"> 가이드 보기 </button>
     </div>
    </div>
   </section><!-- Featured Products Section -->
   <section class="py-20 px-8" id="products">
    <div class="max-w-6xl mx-auto">
     <h2 class="text-4xl font-bold text-gray-900 mb-12" id="featured-title">핫딜 Apple 전자제품</h2>
     <div class="relative">
      <div class="overflow-hidden">
       <div id="carousel-container" class="flex gap-6 transition-transform duration-500">
        <!-- Product Card 1 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="smartphone" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">iPhone 15 Pro</h3>
          <p class="text-gray-600 text-sm mb-4">₩1,499,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 2 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="tablet" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">iPad Air</h3>
          <p class="text-gray-600 text-sm mb-4">₩899,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 3 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="watch" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">Apple Watch 9</h3>
          <p class="text-gray-600 text-sm mb-4">₩399,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 4 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="laptop" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">MacBook Air</h3>
          <p class="text-gray-600 text-sm mb-4">₩1,699,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 5 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="headphones" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">AirPods Pro</h3>
          <p class="text-gray-600 text-sm mb-4">₩449,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 6 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="tablet" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">iPad Pro 12.9"</h3>
          <p class="text-gray-600 text-sm mb-4">₩1,299,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 7 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="smartphone" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">iPhone 15</h3>
          <p class="text-gray-600 text-sm mb-4">₩999,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div><!-- Product Card 8 -->
        <div class="flex-shrink-0 w-1/4 bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md transition">
         <div class="relative bg-gray-100 aspect-square flex items-center justify-center">
          <div class="absolute top-4 left-4 bg-gray-900 text-white px-3 py-1 rounded-full text-xs font-semibold">
           최대 10% 할인
          </div><i data-lucide="watch" style="width: 80px; height: 80px; color: #999;"></i>
         </div>
         <div class="p-5">
          <h3 class="text-gray-900 font-semibold text-lg mb-2">Apple Watch Ultra</h3>
          <p class="text-gray-600 text-sm mb-4">₩799,000</p><button class="w-full bg-gray-900 text-white hover:bg-gray-800 transition font-medium py-2 rounded-lg text-sm"> 지금보기 </button>
         </div>
        </div>
       </div>
      </div><!-- Navigation Buttons --> <button id="prev-btn" class="absolute left-0 top-1/2 -translate-y-1/2 -translate-x-16 bg-gray-900 text-white hover:bg-gray-800 transition w-12 h-12 rounded-full flex items-center justify-center"> <i data-lucide="chevron-left" style="width: 24px; height: 24px;"></i> </button> <button id="next-btn" class="absolute right-0 top-1/2 -translate-y-1/2 translate-x-16 bg-gray-900 text-white hover:bg-gray-800 transition w-12 h-12 rounded-full flex items-center justify-center"> <i data-lucide="chevron-right" style="width: 24px; height: 24px;"></i> </button>
     </div>
    </div>
   </section><!-- Security Section -->
   <section class="py-20 px-8 bg-white" id="benefits">
    <div class="max-w-6xl mx-auto">
     <h2 class="text-4xl font-bold text-gray-900 mb-12 text-center" id="security-title">안전한 코인 결제</h2>
     <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Feature 1 -->
      <div class="text-center">
       <div class="w-20 h-20 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
        <i data-lucide="shield" style="width: 40px; height: 40px; color: #666;"></i>
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">보안 결제</h3>
       <p class="text-gray-600">최고 수준의 암호화 기술로 안전한 거래를 보장합니다.</p>
      </div><!-- Feature 2 -->
      <div class="text-center">
       <div class="w-20 h-20 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
        <i data-lucide="activity" style="width: 40px; height: 40px; color: #666;"></i>
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">즉시 연동</h3>
       <p class="text-gray-600">주요 거래소와 연동되어 빠른 코인 전송이 가능합니다.</p>
      </div><!-- Feature 3 -->
      <div class="text-center">
       <div class="w-20 h-20 bg-gray-100 rounded-full flex items-center justify-center mx-auto mb-6">
        <i data-lucide="message-circle" style="width: 40px; height: 40px; color: #666;"></i>
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">실시간 문의</h3>
       <p class="text-gray-600">즉시 응답하는 라이브 채팅으로 문제를 해결하세요.</p>
      </div>
     </div>
    </div>
   </section><!-- Payment Method Section -->
   <section class="py-20 px-8">
    <div class="max-w-6xl mx-auto">
     <h2 class="text-4xl font-bold text-gray-900 mb-12 text-center" id="method-title">코인 결제 방법</h2>
     <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Step 1 -->
      <div class="bg-white rounded-xl p-8 shadow-sm text-center">
       <div class="w-16 h-16 bg-gray-900 text-white rounded-full flex items-center justify-center mx-auto mb-6 font-bold text-2xl">
        1
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">결제하기</h3>
       <p class="text-gray-600 text-sm">원하는 상품을 선택하고 결제 정보를 입력하세요.</p>
      </div><!-- Step 2 -->
      <div class="bg-white rounded-xl p-8 shadow-sm text-center">
       <div class="w-16 h-16 bg-gray-900 text-white rounded-full flex items-center justify-center mx-auto mb-6 font-bold text-2xl">
        2
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">코인 전송</h3>
       <p class="text-gray-600 text-sm">지정된 지갑 주소로 코인을 전송하세요.</p>
      </div><!-- Step 3 -->
      <div class="bg-white rounded-xl p-8 shadow-sm text-center">
       <div class="w-16 h-16 bg-gray-900 text-white rounded-full flex items-center justify-center mx-auto mb-6 font-bold text-2xl">
        3
       </div>
       <h3 class="text-xl font-semibold text-gray-900 mb-3">구매 완료</h3>
       <p class="text-gray-600 text-sm">확인 후 상품이 배송됩니다. 할인 혜택을 받으세요!</p>
      </div>
     </div>
    </div>
   </section><!-- CTA Banner -->
   <section class="py-20 px-8 bg-gray-900">
    <div class="max-w-6xl mx-auto text-center">
     <h2 class="text-4xl font-bold text-white mb-8" id="cta-banner">지금 바로 쇼핑을 시작하세요!</h2><button class="bg-white text-gray-900 hover:bg-gray-100 transition font-semibold px-10 py-4 rounded-lg text-lg"> 시작하기 </button>
    </div>
   </section><!-- Footer -->
   <footer class="bg-white border-t border-gray-200 py-12 px-8 mt-auto">
    <div class="max-w-6xl mx-auto">
     <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
      <div>
       <h4 class="font-semibold text-gray-900 mb-4">회사 정보</h4>
       <p class="text-gray-600 text-sm">Crypto Commerce는 안전한 코인 결제를 제공하는 전자상거래 플랫폼입니다.</p>
      </div>
      <div>
       <h4 class="font-semibold text-gray-900 mb-4">약관</h4>
       <ul class="space-y-2 text-sm text-gray-600">
        <li><a href="#" class="hover:text-gray-900">이용약관</a></li>
        <li><a href="#" class="hover:text-gray-900">개인정보 처리방침</a></li>
        <li><a href="#" class="hover:text-gray-900">환불 정책</a></li>
       </ul>
      </div>
      <div>
       <h4 class="font-semibold text-gray-900 mb-4">고객센터</h4>
       <ul class="space-y-2 text-sm text-gray-600">
        <li><a href="#" class="hover:text-gray-900">FAQ</a></li>
        <li><a href="#" class="hover:text-gray-900">문의하기</a></li>
        <li><a href="#" class="hover:text-gray-900">공지사항</a></li>
       </ul>
      </div>
     </div>
     <div class="border-t border-gray-200 pt-8 text-center text-gray-600 text-sm">
      <p>© 2024 Crypto Commerce. All rights reserved.</p>
     </div>
    </div>
   </footer>
  </div>
  <script>
    lucide.createIcons();

    // Carousel functionality
    let currentIndex = 0;
    const carouselContainer = document.getElementById('carousel-container');
    const cardWidth = carouselContainer.children[0].offsetWidth;
    const gap = 24; // gap-6 in pixels
    const cardWithGap = cardWidth + gap;

    function updateCarousel() {
      const offset = -currentIndex * cardWithGap;
      carouselContainer.style.transform = `translateX(${offset}px)`;
    }

    document.getElementById('next-btn').addEventListener('click', () => {
      if (currentIndex < carouselContainer.children.length - 4) {
        currentIndex++;
      } else {
        currentIndex = 0;
      }
      updateCarousel();
    });

    document.getElementById('prev-btn').addEventListener('click', () => {
      if (currentIndex > 0) {
        currentIndex--;
      } else {
        currentIndex = carouselContainer.children.length - 4;
      }
      updateCarousel();
    });

    // Auto-scroll every 5 seconds
    setInterval(() => {
      document.getElementById('next-btn').click();
    }, 5000);

    // Element SDK initialization
    const defaultConfig = {
      logo_text: "LOGO",
      hero_title: "코인으로 더 저렴하게 쇼핑하세요!",
      hero_subtitle: "USDT 결제 시 최대 10% 할인",
      featured_section_title: "핫딜 Apple 전자제품",
      security_section_title: "안전한 코인 결제",
      method_section_title: "코인 결제 방법",
      cta_banner_text: "지금 바로 쇼핑을 시작하세요!"
    };

    const element = {
      defaultConfig,
      async onConfigChange(config) {
        document.getElementById("logo-text").textContent = config.logo_text || defaultConfig.logo_text;
        document.getElementById("hero-title").textContent = config.hero_title || defaultConfig.hero_title;
        document.getElementById("hero-subtitle").textContent = config.hero_subtitle || defaultConfig.hero_subtitle;
        document.getElementById("featured-title").textContent = config.featured_section_title || defaultConfig.featured_section_title;
        document.getElementById("security-title").textContent = config.security_section_title || defaultConfig.security_section_title;
        document.getElementById("method-title").textContent = config.method_section_title || defaultConfig.method_section_title;
        document.getElementById("cta-banner").textContent = config.cta_banner_text || defaultConfig.cta_banner_text;
      },
      mapToCapabilities() {
        return {
          recolorables: [],
          borderables: [],
          fontEditable: undefined,
          fontSizeable: undefined
        };
      },
      mapToEditPanelValues(config) {
        return new Map([
          ["logo_text", config.logo_text || defaultConfig.logo_text],
          ["hero_title", config.hero_title || defaultConfig.hero_title],
          ["hero_subtitle", config.hero_subtitle || defaultConfig.hero_subtitle],
          ["featured_section_title", config.featured_section_title || defaultConfig.featured_section_title],
          ["security_section_title", config.security_section_title || defaultConfig.security_section_title],
          ["method_section_title", config.method_section_title || defaultConfig.method_section_title],
          ["cta_banner_text", config.cta_banner_text || defaultConfig.cta_banner_text]
        ]);
      }
    };

    if (window.elementSdk) {
      window.elementSdk.init(element);
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9e67d0807084ea12',t:'MTc3NTIxNjU5NC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
