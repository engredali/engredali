```html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>التحول الرقمي الذكي - نظام السوبر ماركت</title>
    
    <!-- Google Fonts: Cairo -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <!-- Tailwind Config for Custom Colors and Fonts -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Cairo', 'sans-serif'],
                    },
                    colors: {
                        primary: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            800: '#1e40af',
                            900: '#1e3a8a', // Dark blue (Brand color)
                        }
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background-color: #f8fafc;
        }
        .hero-pattern {
            background-color: #1e3a8a;
            background-image: radial-gradient(#3b82f6 1px, transparent 1px);
            background-size: 20px 20px;
        }
    </style>
</head>
<body class="text-gray-800 antialiased selection:bg-blue-200 selection:text-blue-900">

    <!-- Hero Section -->
    <header class="hero-pattern text-white py-20 px-4 shadow-lg relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent to-blue-900/90"></div>
        <div class="max-w-4xl mx-auto text-center relative z-10">
            <div class="inline-flex items-center justify-center p-3 bg-white/10 rounded-full mb-6 backdrop-blur-sm border border-white/20">
                <i data-lucide="monitor-smartphone" class="w-8 h-8 text-blue-200 ml-3"></i>
                <span class="text-blue-100 font-semibold tracking-wide">مشروع التحول الرقمي</span>
            </div>
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold mb-6 leading-tight">
                نظام إدارة وإدخال البيانات <br> 
                <span class="text-blue-300">المخصص للسوبر ماركت</span>
            </h1>
            <p class="text-xl md:text-2xl text-blue-100 mb-8 max-w-3xl mx-auto font-light leading-relaxed">
                حلول سريعة، دقيقة، وآمنة بديلة للطرق التقليدية وبرامج الأوفيس. صُمم لتسريع عمل الموظفين ومنح الإدارة تحكماً كاملاً.
            </p>
            <a href="#details" class="inline-flex items-center gap-2 bg-white text-blue-900 px-8 py-4 rounded-full font-bold text-lg hover:bg-blue-50 transition-all transform hover:scale-105 shadow-xl">
                استعراض تفاصيل المشروع
                <i data-lucide="arrow-down" class="w-5 h-5"></i>
            </a>
        </div>
    </header>

    <!-- Main Content Container -->
    <main id="details" class="max-w-7xl mx-auto px-4 py-16">
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

            <!-- Card 1: Challenges -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 hover:shadow-xl transition-all duration-300 relative overflow-hidden group">
                <div class="absolute top-0 right-0 w-2 h-full bg-red-500"></div>
                <div class="w-14 h-14 bg-red-50 rounded-2xl flex items-center justify-center mb-6 text-red-500 group-hover:scale-110 transition-transform">
                    <i data-lucide="alert-triangle" class="w-8 h-8"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 text-gray-900">التحديات الحالية</h3>
                <ul class="space-y-3 text-gray-600">
                    <li class="flex items-start gap-3">
                        <i data-lucide="x-circle" class="w-5 h-5 text-red-400 shrink-0 mt-0.5"></i>
                        <span><strong>بطء الإدخال:</strong> الإكسيل يبطئ تسجيل مئات الأصناف.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="x-circle" class="w-5 h-5 text-red-400 shrink-0 mt-0.5"></i>
                        <span><strong>تضارب البيانات:</strong> صعوبة عمل عدة موظفين معاً بدون أخطاء.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="x-circle" class="w-5 h-5 text-red-400 shrink-0 mt-0.5"></i>
                        <span><strong>ضعف الأمان:</strong> ملفات الأوفيس قابلة للنسخ أو الحذف العشوائي.</span>
                    </li>
                </ul>
            </div>

            <!-- Card 2: Solution -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 hover:shadow-xl transition-all duration-300 relative overflow-hidden group">
                <div class="absolute top-0 right-0 w-2 h-full bg-blue-500"></div>
                <div class="w-14 h-14 bg-blue-50 rounded-2xl flex items-center justify-center mb-6 text-blue-600 group-hover:scale-110 transition-transform">
                    <i data-lucide="lightbulb" class="w-8 h-8"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 text-gray-900">الحل المقترح</h3>
                <ul class="space-y-3 text-gray-600">
                    <li class="flex items-start gap-3">
                        <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-500 shrink-0 mt-0.5"></i>
                        <span><strong>نظام ويب داخلي:</strong> تطبيق يعمل عبر متصفح الإنترنت على شبكة محلية.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-500 shrink-0 mt-0.5"></i>
                        <span><strong>سهولة فائقة:</strong> لا حاجة لتثبيت برامج معقدة؛ مجرد رابط يفتح النظام.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-500 shrink-0 mt-0.5"></i>
                        <span><strong>تخصيص كامل:</strong> مصمم ليناسب طريقة عمل هذا السوبر ماركت تحديداً.</span>
                    </li>
                </ul>
            </div>

            <!-- Card 3: Employee Features -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 hover:shadow-xl transition-all duration-300 relative overflow-hidden group">
                <div class="absolute top-0 right-0 w-2 h-full bg-green-500"></div>
                <div class="w-14 h-14 bg-green-50 rounded-2xl flex items-center justify-center mb-6 text-green-600 group-hover:scale-110 transition-transform">
                    <i data-lucide="zap" class="w-8 h-8"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 text-gray-900">مميزات للموظفين</h3>
                <ul class="space-y-3 text-gray-600">
                    <li class="flex items-start gap-3">
                        <i data-lucide="barcode" class="w-5 h-5 text-green-500 shrink-0 mt-0.5"></i>
                        <span><strong>تكامل الباركود:</strong> يقرأ الباركود وينتقل للحقل التالي تلقائياً للسرعة.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="layout-template" class="w-5 h-5 text-green-500 shrink-0 mt-0.5"></i>
                        <span><strong>نماذج ذكية:</strong> تمنع إدخال بيانات خاطئة كأخطاء تسعير البيع والشراء.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="smartphone" class="w-5 h-5 text-green-500 shrink-0 mt-0.5"></i>
                        <span><strong>جرد متنقل:</strong> يمكن فتح النظام من تابلت أثناء الوقوف في الممرات.</span>
                    </li>
                </ul>
            </div>

            <!-- Card 4: Management Features -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 hover:shadow-xl transition-all duration-300 relative overflow-hidden group md:col-span-2 lg:col-span-1">
                <div class="absolute top-0 right-0 w-2 h-full bg-purple-500"></div>
                <div class="w-14 h-14 bg-purple-50 rounded-2xl flex items-center justify-center mb-6 text-purple-600 group-hover:scale-110 transition-transform">
                    <i data-lucide="shield-check" class="w-8 h-8"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 text-gray-900">رقابة الإدارة</h3>
                <ul class="space-y-3 text-gray-600">
                    <li class="flex items-start gap-3">
                        <i data-lucide="users" class="w-5 h-5 text-purple-500 shrink-0 mt-0.5"></i>
                        <span><strong>نظام الصلاحيات:</strong> تحكم كامل بمن يرى ويعدل البيانات الحساسة والأرباح.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="history" class="w-5 h-5 text-purple-500 shrink-0 mt-0.5"></i>
                        <span><strong>سجل التتبع (Audit Log):</strong> معرفة من قام بالإضافة أو التعديل بالوقت والتاريخ.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="pie-chart" class="w-5 h-5 text-purple-500 shrink-0 mt-0.5"></i>
                        <span><strong>تقارير فورية:</strong> نواقص المخزون وحركة إدخال الموظفين بضغطة زر.</span>
                    </li>
                </ul>
            </div>

            <!-- Card 5: Tech & Security -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 p-8 hover:shadow-xl transition-all duration-300 relative overflow-hidden group md:col-span-2 lg:col-span-2">
                <div class="absolute top-0 right-0 w-2 h-full bg-slate-700"></div>
                <div class="w-14 h-14 bg-slate-100 rounded-2xl flex items-center justify-center mb-6 text-slate-700 group-hover:scale-110 transition-transform">
                    <i data-lucide="database" class="w-8 h-8"></i>
                </div>
                <h3 class="text-2xl font-bold mb-4 text-gray-900">التقنية والأمان</h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-4">
                    <ul class="space-y-3 text-gray-600">
                        <li class="flex items-start gap-3">
                            <i data-lucide="server" class="w-5 h-5 text-slate-500 shrink-0 mt-0.5"></i>
                            <span><strong>قاعدة بيانات مركزية:</strong> تتحمل دخول جميع الموظفين في نفس اللحظة بدون فقدان للبيانات، بديلة للإكسيل.</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <i data-lucide="network" class="w-5 h-5 text-slate-500 shrink-0 mt-0.5"></i>
                            <span><strong>أمان الشبكة المحلية:</strong> النظام يعمل داخل شبكة الماركت مما يحميه من الاختراقات الخارجية أو انقطاع الإنترنت.</span>
                        </li>
                    </ul>
                    <div class="bg-slate-50 rounded-xl p-6 border border-slate-100 flex items-center justify-center text-center">
                        <div>
                            <i data-lucide="blocks" class="w-10 h-10 text-slate-400 mx-auto mb-3"></i>
                            <h4 class="font-bold text-slate-800 mb-2">قابلية التوسع مستقبلاً</h4>
                            <p class="text-sm text-slate-500">النظام مصمم ليقبل الربط لاحقاً مع نقاط الكاشير (POS) أو تطبيقات التوصيل بسهولة تامة.</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Implementation Plan Section -->
        <div class="mt-16 bg-blue-900 rounded-3xl p-8 md:p-12 text-white relative overflow-hidden shadow-2xl">
            <div class="absolute top-0 left-0 w-full h-full opacity-10 pointer-events-none" style="background-image: radial-gradient(circle at 2px 2px, white 1px, transparent 0); background-size: 32px 32px;"></div>
            
            <div class="relative z-10">
                <div class="flex items-center gap-4 mb-10">
                    <div class="p-3 bg-blue-800 rounded-xl">
                        <i data-lucide="git-pull-request" class="w-8 h-8 text-blue-300"></i>
                    </div>
                    <h2 class="text-3xl font-bold">خطة العمل والتنفيذ</h2>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Step 1 -->
                    <div class="bg-blue-800/50 rounded-2xl p-6 backdrop-blur-sm border border-blue-700">
                        <div class="w-10 h-10 bg-blue-500 text-white rounded-full flex items-center justify-center font-bold text-xl mb-4 shadow-lg">1</div>
                        <h4 class="text-xl font-bold mb-3">النموذج الأولي</h4>
                        <p class="text-blue-100 text-sm leading-relaxed">برمجة النسخة الأساسية (إضافة صنف، الباركود، والبحث) لتجربتها على أرض الواقع وتقييم الأداء.</p>
                    </div>
                    
                    <!-- Step 2 -->
                    <div class="bg-blue-800/50 rounded-2xl p-6 backdrop-blur-sm border border-blue-700">
                        <div class="w-10 h-10 bg-blue-500 text-white rounded-full flex items-center justify-center font-bold text-xl mb-4 shadow-lg">2</div>
                        <h4 class="text-xl font-bold mb-3">التجربة والتدريب</h4>
                        <p class="text-blue-100 text-sm leading-relaxed">تدريب موظف على النظام وأخذ ملاحظاته لتحسين الواجهة وتسريع عملية إدخال البيانات قدر الإمكان.</p>
                    </div>

                    <!-- Step 3 -->
                    <div class="bg-blue-800/50 rounded-2xl p-6 backdrop-blur-sm border border-blue-700">
                        <div class="w-10 h-10 bg-blue-500 text-white rounded-full flex items-center justify-center font-bold text-xl mb-4 shadow-lg">3</div>
                        <h4 class="text-xl font-bold mb-3">الإطلاق المكتمل</h4>
                        <p class="text-blue-100 text-sm leading-relaxed">إضافة نظام الصلاحيات الإدارية والتقارير، واعتماد النظام رسمياً بدلاً من كافة الأنظمة التقليدية القديمة.</p>
                    </div>
                </div>
            </div>
        </div>

    </main>

    <!-- Footer -->
    <footer class="bg-white border-t border-gray-200 py-8 text-center text-gray-500 mt-8">
        <p>مُقترح مشروع نظام إدارة السوبر ماركت الذكي &copy; 2024</p>
    </footer>

    <!-- Initialize Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>

```
 at your changes.
--->
