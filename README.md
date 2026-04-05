# site[original_code.html](https://github.com/user-attachments/files/26487560/original_code.html)
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
        </div>
       </div>
      </div>
     </div>
    </div>
   </section>
  </div>
  <script>
    lucide.createIcons();
  </script>
 </body>
</html>
