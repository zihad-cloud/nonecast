**<!DOCTYPE html>**

**<html lang="en">**

&#x20; **<head>**

&#x20;   **<meta charset="UTF-8" />**

&#x20;   **<meta name="viewport" content="width=device-width, initial-scale=1.0" />**

&#x20;   **<title>Screen</title>**

&#x20;   **<link rel="preconnect" href="https://fonts.googleapis.com" />**

&#x20;   **<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />**

&#x20;   **<link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900\&family=Poppins:wght@100..900\&family=Fira+Code:wght@300..700\&family=Plus+Jakarta+Sans:wght@200;300;400;500;600;700;800\&display=swap" rel="stylesheet" />**

&#x20;   **<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>**

&#x20;   **<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>**

&#x20;   **<script src="https://code.iconify.design/iconify-icon/3.0.0/iconify-icon.min.js"></script>**

&#x20;   **<style type="text/tailwindcss">**

&#x20;     **@import "tailwindcss";**

&#x20;     **@theme inline {**

&#x20;       **--color-background: var(--background);**

&#x20;       **--color-foreground: var(--foreground);**

&#x20;       **--color-primary: var(--primary);**

&#x20;       **--color-primary-foreground: var(--primary-foreground);**

&#x20;       **--color-secondary: var(--secondary);**

&#x20;       **--color-secondary-foreground: var(--secondary-foreground);**

&#x20;       **--color-tertiary: var(--tertiary);**

&#x20;       **--color-muted: var(--muted);**

&#x20;       **--color-muted-foreground: var(--muted-foreground);**

&#x20;       **--color-accent: var(--accent);**

&#x20;       **--color-destructive: var(--destructive);**

&#x20;       **--color-card: var(--card);**

&#x20;       **--color-card-foreground: var(--card-foreground);**

&#x20;       **--color-border: var(--border);**

&#x20;       **--color-input: var(--input);**

&#x20;       **--color-ring: var(--ring);**

&#x20;       **--radius-sm: calc(var(--radius) - 4px);**

&#x20;       **--radius-md: calc(var(--radius) - 2px);**

&#x20;       **--radius-lg: var(--radius);**

&#x20;       **--font-family-sans: var(--font-sans);**

&#x20;       **--font-family-heading: var(--font-heading);**

&#x20;     **}**

&#x20;     **:root { --ring: #006A4E;**

&#x20;       **--input: #E2E8F0;**

&#x20;       **--primary-foreground: #FFFFFF;**

&#x20;       **--border: #E2E8F0;**

&#x20;       **--radius: 0.25rem;**

&#x20;       **--muted-foreground: #64748B;**

&#x20;       **--muted: #F8FAFC;**

&#x20;       **--secondary: #0F172A;**

&#x20;       **--background: #FFFFFF;**

&#x20;       **--primary: #006A4E;**

&#x20;       **--secondary-foreground: #FFFFFF;**

&#x20;       **--card: #FFFFFF;**

&#x20;       **--tertiary: #006A4E;**

&#x20;       **--foreground: #0F172A; }**

&#x20;   **</style>**

&#x20; **</head>**

&#x20; **<body>**

**<div class="min-h-screen w-full bg-background flex flex-col relative font-sans">**

&#x20; **<!-- Reading Progress Bar -->**

&#x20; **<div class="fixed top-0 left-0 w-full h-1.5 z-\[60] bg-muted">**

&#x20;   **<div class="h-full bg-primary w-1/3 shadow-\[0\_0\_10px\_rgba(0,106,78,0.5)]"></div>**

&#x20; **</div>**



&#x20; **<!-- Header -->**

&#x20; **<header class="border-b border-border bg-white sticky top-0 z-50">**

&#x20;   **<div class="max-w-7xl mx-auto px-4 h-16 flex items-center justify-between">**

&#x20;     **<div class="flex items-center gap-4">**

&#x20;       **<button class="p-2 hover:bg-muted rounded-full lg:hidden"><iconify-icon icon="lucide:menu" class="text-xl"></iconify-icon></button>**

&#x20;       **<div class="flex items-center gap-3">**

&#x20;         **<div class="bg-primary p-1.5 rounded shadow-sm">**

&#x20;           **<iconify-icon icon="lucide:sun" class="text-xl text-white"></iconify-icon>**

&#x20;         **</div>**

&#x20;         **<div class="flex flex-col -space-y-1">**

&#x20;           **<span class="font-heading font-bold text-lg text-secondary">THE RISING <span class="text-primary">CAMPUS</span></span>**

&#x20;           **<span class="text-\[8px] font-bold text-primary/80 uppercase tracking-widest">দ্য রাইজিং ক্যাম্পাস</span>**

&#x20;         **</div>**

&#x20;       **</div>**

&#x20;     **</div>**

&#x20;     

&#x20;     **<div class="flex items-center gap-6">**

&#x20;       **<!-- Language Switcher -->**

&#x20;       **<div class="hidden sm:flex items-center border border-border rounded-lg overflow-hidden text-\[10px] font-bold">**

&#x20;         **<button class="px-3 py-1.5 bg-primary text-white">বাংলা</button>**

&#x20;         **<button class="px-3 py-1.5 hover:bg-muted transition-colors">EN</button>**

&#x20;       **</div>**

&#x20;       

&#x20;       **<div class="flex items-center gap-3">**

&#x20;         **<button class="p-2 hover:bg-muted rounded-full transition-colors"><iconify-icon icon="lucide:search" class="text-xl"></iconify-icon></button>**

&#x20;         **<button class="bg-primary text-white px-5 py-2 rounded-lg text-xs font-bold hidden md:block hover:bg-primary/90 transition-all shadow-md shadow-primary/20">সদস্য হোন (Subscribe)</button>**

&#x20;       **</div>**

&#x20;     **</div>**

&#x20;   **</div>**

&#x20; **</header>**



&#x20; **<main class="max-w-7xl mx-auto px-4 py-8 lg:py-12 flex-1 w-full">**

&#x20;   **<div class="grid grid-cols-1 lg:grid-cols-12 gap-12">**

&#x20;     

&#x20;     **<!-- Social Sharing Sticky (Desktop) -->**

&#x20;     **<aside class="hidden lg:block lg:col-span-1">**

&#x20;       **<div class="sticky top-32 space-y-4 flex flex-col items-center">**

&#x20;         **<button class="w-11 h-11 rounded-full border border-border flex items-center justify-center hover:bg-primary hover:text-white hover:border-primary transition-all shadow-sm group">**

&#x20;           **<iconify-icon icon="lucide:facebook" class="text-lg"></iconify-icon>**

&#x20;         **</button>**

&#x20;         **<button class="w-11 h-11 rounded-full border border-border flex items-center justify-center hover:bg-primary hover:text-white hover:border-primary transition-all shadow-sm group">**

&#x20;           **<iconify-icon icon="lucide:twitter" class="text-lg"></iconify-icon>**

&#x20;         **</button>**

&#x20;         **<button class="w-11 h-11 rounded-full border border-border flex items-center justify-center hover:bg-primary hover:text-white hover:border-primary transition-all shadow-sm group">**

&#x20;           **<iconify-icon icon="lucide:link" class="text-lg"></iconify-icon>**

&#x20;         **</button>**

&#x20;         **<div class="h-10 w-px bg-border"></div>**

&#x20;         **<button class="w-11 h-11 rounded-full border border-border flex items-center justify-center hover:bg-muted transition-all shadow-sm">**

&#x20;           **<iconify-icon icon="lucide:bookmark" class="text-lg"></iconify-icon>**

&#x20;         **</button>**

&#x20;         **<button class="w-11 h-11 rounded-full border border-border flex items-center justify-center hover:bg-muted transition-all shadow-sm">**

&#x20;           **<iconify-icon icon="lucide:message-circle" class="text-lg"></iconify-icon>**

&#x20;         **</button>**

&#x20;       **</div>**

&#x20;     **</aside>**



&#x20;     **<!-- Article Content -->**

&#x20;     **<article class="lg:col-span-7">**

&#x20;       **<!-- Breadcrumbs -->**

&#x20;       **<nav class="flex items-center gap-2 text-\[10px] font-bold text-muted-foreground mb-8 uppercase tracking-widest">**

&#x20;         **<a href="#" class="hover:text-primary">প্রচ্ছদ (Home)</a>**

&#x20;         **<iconify-icon icon="lucide:arrow-right" class="text-\[8px]"></iconify-icon>**

&#x20;         **<a href="#" class="hover:text-primary">শিক্ষা (Education)</a>**

&#x20;         **<iconify-icon icon="lucide:arrow-right" class="text-\[8px]"></iconify-icon>**

&#x20;         **<span class="text-primary">সংবাদ (News)</span>**

&#x20;       **</nav>**



&#x20;       **<header class="mb-10">**

&#x20;         **<div class="flex items-center gap-3 mb-6">**

&#x20;           **<span class="bg-primary/10 text-primary px-3 py-1 rounded-full text-\[10px] font-bold uppercase tracking-wider">শিক্ষা (Education)</span>**

&#x20;           **<span class="text-muted-foreground text-\[10px] font-bold flex items-center gap-1"><iconify-icon icon="lucide:clock" class="text-sm"></iconify-icon> ৮ মিনিট পাঠ (8 min read)</span>**

&#x20;         **</div>**

&#x20;         

&#x20;         **<h1 class="text-4xl md:text-5xl font-heading font-black leading-tight text-secondary mb-6">উচ্চশিক্ষা প্রতিষ্ঠানে নতুন ডিজিটাল ফ্রেমওয়ার্ক ঘোষণা সরকারের</h1>**

&#x20;         **<h2 class="text-xl md:text-2xl font-sans font-medium text-muted-foreground leading-relaxed mb-8 border-l-4 border-primary pl-6">শিক্ষা মন্ত্রণালয় ২০২৬ সালের মধ্যে ৫০টিরও বেশি পাবলিক বিশ্ববিদ্যালয়কে ডিজিটালাইজ করার একটি বিস্তৃত রোডম্যাপ উন্মোচন করেছে।</h2>**

&#x20;         

&#x20;         **<div class="flex items-center justify-between py-6 border-y border-border">**

&#x20;           **<div class="flex items-center gap-4">**

&#x20;             **<img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-14 h-14 rounded-full object-cover border-2 border-primary/10" alt="Author">**

&#x20;             **<div>**

&#x20;               **<p class="text-sm font-bold text-secondary">মো. সাইদুল ইসলাম (Sayedul Islam)</p>**

&#x20;               **<p class="text-xs text-muted-foreground">প্রধান সম্পাদকীয় সংবাদদাতা</p>**

&#x20;             **</div>**

&#x20;           **</div>**

&#x20;           **<div class="text-right hidden sm:block">**

&#x20;             **<p class="text-\[10px] font-bold text-muted-foreground uppercase tracking-widest">প্রকাশিত (Published)</p>**

&#x20;             **<p class="text-xs font-bold text-secondary">২২ মে, ২০২৪ • সকাল ১০:৩০</p>**

&#x20;           **</div>**

&#x20;         **</div>**

&#x20;       **</header>**



&#x20;       **<figure class="mb-12">**

&#x20;         **<div class="rounded-2xl overflow-hidden shadow-xl border border-border mb-4">**

&#x20;           **<img src="https://uxmagic.blob.core.windows.net/public/agent-images/hero-news-1780522445680-rdxku7bpb6.png" class="w-full h-auto" alt="Article Visual">**

&#x20;         **</div>**

&#x20;         **<figcaption class="text-xs text-muted-foreground text-center italic font-medium">**

&#x20;           **নতুন ফ্রেমওয়ার্কের লক্ষ্য দেশজুড়ে ক্যাম্পাস অবকাঠামো আধুনিকীকরণ। ছবি: দ্য রাইজিং ক্যাম্পাস**

&#x20;         **</figcaption>**

&#x20;       **</figure>**



&#x20;       **<div class="prose prose-slate max-w-none text-lg leading-relaxed text-secondary space-y-8 font-sans">**

&#x20;         **<p class="first-letter:text-5xl first-letter:font-bold first-letter:text-primary first-letter:mr-3 first-letter:float-left">বাংলাদেশ সরকার আনুষ্ঠানিকভাবে "স্মার্ট ক্যাম্পাস ইনিশিয়েটিভ" অনুমোদন করেছে, যা পাবলিক বিশ্ববিদ্যালয়গুলোর ডিজিটাল অবকাঠামোতে বিপ্লব ঘটানোর লক্ষ্যে একটি বহুমুখী প্রকল্প। আজ সকালে সচিবালয়ে আয়োজিত এক সংবাদ সম্মেলনে শিক্ষামন্ত্রী এই ঘোষণা দেন।</p>**

&#x20;         

&#x20;         **<p>এই নতুন কাঠামোর অধীনে, দেশের প্রতিটি পাবলিক বিশ্ববিদ্যালয় উচ্চ-গতির ফাইবার অপটিক কানেক্টিভিটি, কেন্দ্রীয় ডিজিটাল লাইব্রেরি এবং অত্যাধুনিক এআই গবেষণা ল্যাবরেটরিতে সজ্জিত হবে। প্রকল্পটি তিনটি ধাপে সম্পন্ন হবে বলে আশা করা হচ্ছে, যার প্রথম ধাপে ২০২৪ সালের শেষের দিকে প্রধান বিভাগীয় বিশ্ববিদ্যালয়গুলোকে লক্ষ্য করা হয়েছে।</p>**

&#x20;         

&#x20;         **<blockquote class="bg-muted p-10 rounded-2xl border-l-8 border-primary my-12 shadow-sm">**

&#x20;           **<p class="text-2xl font-heading font-bold italic mb-6 text-primary leading-tight">"আমাদের লক্ষ্য হলো প্রতিটি শিক্ষার্থী, তাদের অবস্থান নির্বিশেষে, বিশ্বমানের ডিজিটাল রিসোর্স ব্যবহারের সুযোগ পায় তা নিশ্চিত করা।"</p>**

&#x20;           **<footer class="text-sm font-bold text-secondary flex items-center gap-2">**

&#x20;             **<span class="w-8 h-px bg-primary"></span> শিক্ষামন্ত্রী, গণপ্রজাতন্ত্রী বাংলাদেশ সরকার**

&#x20;           **</footer>**

&#x20;         **</blockquote>**



&#x20;         **<p>উদ্যোগের মূল বৈশিষ্ট্যগুলোর মধ্যে রয়েছে সকল বিশ্ববিদ্যালয়ের জন্য একটি সমন্বিত লার্নিং ম্যানেজমেন্ট সিস্টেম (LMS), শিক্ষার্থী ও অনুষদের জন্য ডিজিটাল আইডি কার্ড এবং গবেষকদের জন্য একটি নিবেদিত উচ্চ-ক্ষমতাসম্পন্ন কম্পিউটিং ক্লাস্টার। সরকার ভর্তুকিযুক্ত সফটওয়্যার লাইসেন্স এবং বিশেষ প্রশিক্ষণের জন্য আন্তর্জাতিক প্রযুক্তি জায়ান্টদের সাথে অংশীদারিত্ব করেছে।</p>**

&#x20;         

&#x20;         **<h3 class="text-2xl font-heading font-bold pt-6 text-secondary flex items-center gap-3">**

&#x20;           **<span class="w-2 h-8 bg-primary rounded-full"></span> বাস্তবায়ন কৌশল (Strategy)**

&#x20;         **</h3>**

&#x20;         **<p>বিশ্ববিদ্যালয় মঞ্জুরি কমিশন (ইউজিসি) প্রকল্পের বাস্তবায়ন তদারকি করবে। অবকাঠামো কাজের স্বচ্ছতা এবং সময়মত সমাপ্তি নিশ্চিত করার জন্য একটি নিবেদিত পর্যবেক্ষণ সেল গঠন করা হয়েছে। এই উদ্যোগের জন্য অর্থায়ন জাতীয় বাজেট থেকে করা হবে এবং আন্তর্জাতিক উন্নয়ন সহযোগীদের কাছ থেকে অতিরিক্ত সহায়তা নেওয়া হবে।</p>**

&#x20;       **</div>**



&#x20;       **<!-- Tags -->**

&#x20;       **<div class="mt-16 pt-8 border-t border-border flex flex-wrap gap-3">**

&#x20;         **<span class="text-\[10px] font-bold text-muted-foreground mr-2 self-center uppercase tracking-widest">ট্যাগসমূহ:</span>**

&#x20;         **<a href="#" class="px-4 py-1.5 bg-muted rounded-lg text-xs font-bold hover:bg-primary hover:text-white transition-all">শিক্ষা</a>**

&#x20;         **<a href="#" class="px-4 py-1.5 bg-muted rounded-lg text-xs font-bold hover:bg-primary hover:text-white transition-all">ডিজিটাল বাংলাদেশ</a>**

&#x20;         **<a href="#" class="px-4 py-1.5 bg-muted rounded-lg text-xs font-bold hover:bg-primary hover:text-white transition-all">বিশ্ববিদ্যালয়</a>**

&#x20;         **<a href="#" class="px-4 py-1.5 bg-muted rounded-lg text-xs font-bold hover:bg-primary hover:text-white transition-all">প্রযুক্তি</a>**

&#x20;       **</div>**



&#x20;       **<!-- Author Box -->**

&#x20;       **<div class="mt-16 p-10 bg-muted rounded-2xl flex flex-col md:flex-row gap-8 items-center md:items-start text-center md:text-left border border-border/50">**

&#x20;         **<img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-28 h-28 rounded-full border-4 border-white shadow-lg" alt="Author">**

&#x20;         **<div class="space-y-4">**

&#x20;           **<h3 class="text-2xl font-heading font-bold text-secondary">মো. সাইদুল ইসলাম (Sayedul Islam)</h3>**

&#x20;           **<p class="text-base text-muted-foreground leading-relaxed">সাইদুল দ্য রাইজিং ক্যাম্পাসের প্রধান সম্পাদকীয় সংবাদদাতা, তিনি শিক্ষা নীতি এবং ডিজিটাল রূপান্তর বিষয়ে বিশেষজ্ঞ। ১০ বছরেরও বেশি অভিজ্ঞতার সাথে, তিনি প্রধান জাতীয় ইভেন্ট এবং নীতি পরিবর্তনগুলো কভার করেছেন।</p>**

&#x20;           **<div class="flex justify-center md:justify-start gap-5">**

&#x20;             **<a href="#" class="w-10 h-10 rounded-full bg-white flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-all shadow-sm"><iconify-icon icon="lucide:twitter"></iconify-icon></a>**

&#x20;             **<a href="#" class="w-10 h-10 rounded-full bg-white flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-all shadow-sm"><iconify-icon icon="lucide:mail"></iconify-icon></a>**

&#x20;             **<a href="#" class="w-10 h-10 rounded-full bg-white flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-all shadow-sm"><iconify-icon icon="lucide:globe"></iconify-icon></a>**

&#x20;           **</div>**

&#x20;         **</div>**

&#x20;       **</div>**

&#x20;     **</article>**



&#x20;     **<!-- Sidebar -->**

&#x20;     **<aside class="lg:col-span-4 space-y-12">**

&#x20;       **<!-- Ad Placeholder -->**

&#x20;       **<div class="w-full aspect-square bg-muted border border-dashed border-border flex flex-col items-center justify-center text-muted-foreground text-xs text-center p-6 rounded-2xl">**

&#x20;         **<iconify-icon icon="lucide:image" class="text-3xl mb-2 opacity-20"></iconify-icon>**

&#x20;         **বিজ্ঞাপন (Advertisement)<br>(300x300)**

&#x20;       **</div>**



&#x20;       **<!-- Trending Now -->**

&#x20;       **<section class="bg-white rounded-2xl border border-border shadow-sm overflow-hidden">**

&#x20;         **<div class="bg-secondary p-5 flex items-center justify-between">**

&#x20;           **<h3 class="font-heading font-bold text-sm uppercase tracking-widest text-white">জনপ্রিয় সংবাদ (Trending)</h3>**

&#x20;           **<iconify-icon icon="lucide:flame" class="text-orange-500"></iconify-icon>**

&#x20;         **</div>**

&#x20;         **<div class="p-5 space-y-6">**

&#x20;           **<div class="group cursor-pointer flex gap-4 pb-6 border-b border-border/50 last:border-0 last:pb-0">**

&#x20;             **<div class="w-24 h-20 shrink-0 rounded-lg overflow-hidden border border-border shadow-sm">**

&#x20;               **<img src="https://images.unsplash.com/photo-1526628953301-3e589a6a8b74?q=80\&w=200\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" alt="News">**

&#x20;             **</div>**

&#x20;             **<div class="space-y-2">**

&#x20;               **<h4 class="font-bold text-sm leading-tight group-hover:text-primary transition-colors">নীতিমালা আপডেটের পর শেয়ার বাজারে বড় ধরনের উত্থান</h4>**

&#x20;               **<p class="text-\[10px] text-muted-foreground font-bold uppercase tracking-wider flex items-center gap-1"><span class="text-primary">অর্থনীতি</span> • ১ ঘণ্টা আগে</p>**

&#x20;             **</div>**

&#x20;           **</div>**

&#x20;           **<div class="group cursor-pointer flex gap-4 pb-6 border-b border-border/50 last:border-0 last:pb-0">**

&#x20;             **<div class="w-24 h-20 shrink-0 rounded-lg overflow-hidden border border-border shadow-sm">**

&#x20;               **<img src="https://images.unsplash.com/photo-1540747913346-19e32dc3e97e?q=80\&w=200\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" alt="News">**

&#x20;             **</div>**

&#x20;             **<div class="space-y-2">**

&#x20;               **<h4 class="font-bold text-sm leading-tight group-hover:text-primary transition-colors">জাতীয় দলের অধিনায়ক আগাম অবসরের ইঙ্গিত দিলেন</h4>**

&#x20;               **<p class="text-\[10px] text-muted-foreground font-bold uppercase tracking-wider flex items-center gap-1"><span class="text-primary">খেলাধুলা</span> • ৩ ঘণ্টা আগে</p>**

&#x20;             **</div>**

&#x20;           **</div>**

&#x20;           **<div class="group cursor-pointer flex gap-4">**

&#x20;             **<div class="w-24 h-20 shrink-0 rounded-lg overflow-hidden border border-border shadow-sm">**

&#x20;               **<img src="https://images.unsplash.com/photo-1596461404969-9ae70f2830c1?q=80\&w=200\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" alt="News">**

&#x20;             **</div>**

&#x20;             **<div class="space-y-2">**

&#x20;               **<h4 class="font-bold text-sm leading-tight group-hover:text-primary transition-colors">মৌসুমী ফ্লুর জন্য নতুন স্বাস্থ্য নির্দেশিকা জারি</h4>**

&#x20;               **<p class="text-\[10px] text-muted-foreground font-bold uppercase tracking-wider flex items-center gap-1"><span class="text-primary">স্বাস্থ্য</span> • ৫ ঘণ্টা আগে</p>**

&#x20;             **</div>**

&#x20;           **</div>**

&#x20;         **</div>**

&#x20;       **</section>**



&#x20;       **<!-- Newsletter -->**

&#x20;       **<section class="bg-primary p-10 rounded-2xl text-white shadow-lg shadow-primary/20 relative overflow-hidden">**

&#x20;         **<div class="relative z-10">**

&#x20;           **<iconify-icon icon="lucide:mail-plus" class="text-5xl mb-6 opacity-30"></iconify-icon>**

&#x20;           **<h3 class="text-2xl font-heading font-bold mb-3">সর্বশেষ আপডেট পান</h3>**

&#x20;           **<p class="text-sm text-white/80 mb-8 leading-relaxed">৫০,০০০+ পাঠকদের সাথে যোগ দিন এবং প্রতিদিনের শীর্ষ সংবাদ সরাসরি আপনার ইনবক্সে পান।</p>**

&#x20;           **<div class="space-y-4">**

&#x20;             **<input type="email" placeholder="ইমেইল ঠিকানা (Email)" class="w-full bg-white/10 border border-white/20 rounded-lg px-5 py-4 text-sm focus:ring-2 focus:ring-white outline-none text-white placeholder:text-white/50 transition-all">**

&#x20;             **<button class="w-full bg-white text-primary py-4 rounded-lg font-bold text-sm hover:bg-secondary hover:text-white transition-all shadow-md">সাবস্ক্রাইব করুন</button>**

&#x20;           **</div>**

&#x20;         **</div>**

&#x20;         **<iconify-icon icon="lucide:send" class="absolute -bottom-10 -right-10 text-\[180px] text-white/5"></iconify-icon>**

&#x20;       **</section>**

&#x20;     **</aside>**



&#x20;   **</div>**



&#x20;   **<!-- Related News Carousel -->**

&#x20;   **<section class="mt-24 pt-16 border-t border-border">**

&#x20;     **<div class="flex items-center justify-between mb-10">**

&#x20;       **<h2 class="text-3xl font-heading font-bold text-secondary flex items-center gap-3">**

&#x20;         **<span class="w-2 h-8 bg-primary rounded-full"></span> সংশ্লিষ্ট সংবাদ (Related)**

&#x20;       **</h2>**

&#x20;       **<div class="flex gap-3">**

&#x20;         **<button class="w-12 h-12 rounded-full border border-border flex items-center justify-center hover:bg-primary hover:text-white hover:border-primary transition-all shadow-sm"><iconify-icon icon="lucide:arrow-left" class="text-lg"></iconify-icon></button>**

&#x20;         **<button class="w-12 h-12 rounded-full border border-border flex items-center justify-center hover:bg-primary hover:text-white hover:border-primary transition-all shadow-sm"><iconify-icon icon="lucide:arrow-right" class="text-lg"></iconify-icon></button>**

&#x20;       **</div>**

&#x20;     **</div>**

&#x20;     **<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">**

&#x20;       **<div class="group cursor-pointer">**

&#x20;         **<div class="aspect-video rounded-xl overflow-hidden mb-5 border border-border shadow-sm">**

&#x20;           **<img src="https://images.unsplash.com/photo-1523050335102-c6ad80d70bb5?q=80\&w=400\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" alt="Related">**

&#x20;         **</div>**

&#x20;         **<h4 class="font-bold text-base leading-snug group-hover:text-primary transition-colors">অনলাইন পরীক্ষার জন্য নতুন নির্দেশিকা জারি করেছে ইউজিসি</h4>**

&#x20;         **<p class="text-\[10px] text-muted-foreground mt-3 font-bold uppercase tracking-widest flex items-center gap-2">**

&#x20;           **<span class="text-primary">শিক্ষা</span> • ১ দিন আগে**

&#x20;         **</p>**

&#x20;       **</div>**

&#x20;       **<div class="group cursor-pointer">**

&#x20;         **<div class="aspect-video rounded-xl overflow-hidden mb-5 border border-border shadow-sm">**

&#x20;           **<img src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?q=80\&w=400\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" alt="Related">**

&#x20;         **</div>**

&#x20;         **<h4 class="font-bold text-base leading-snug group-hover:text-primary transition-colors">দীর্ঘ ছুটির পর স্বাভাবিক ছন্দে ফিরছে ক্যাম্পাস জীবন</h4>**

&#x20;         **<p class="text-\[10px] text-muted-foreground mt-3 font-bold uppercase tracking-widest flex items-center gap-2">**

&#x20;           **<span class="text-primary">ক্যাম্পাস</span> • ২ দিন আগে**

&#x20;         **</p>**

&#x20;       **</div>**

&#x20;       **<div class="group cursor-pointer">**

&#x20;         **<div class="aspect-video rounded-xl overflow-hidden mb-5 border border-border shadow-sm">**

&#x20;           **<img src="https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80\&w=400\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" alt="Related">**

&#x20;         **</div>**

&#x20;         **<h4 class="font-bold text-base leading-snug group-hover:text-primary transition-colors">বাংলাদেশের শীর্ষ ১০ বিশ্ববিদ্যালয়: ২০২৪ সালের র‍্যাঙ্কিং</h4>**

&#x20;         **<p class="text-\[10px] text-muted-foreground mt-3 font-bold uppercase tracking-widest flex items-center gap-2">**

&#x20;           **<span class="text-primary">র‍্যাঙ্কিং</span> • ৩ দিন আগে**

&#x20;         **</p>**

&#x20;       **</div>**

&#x20;       **<div class="group cursor-pointer">**

&#x20;         **<div class="aspect-video rounded-xl overflow-hidden mb-5 border border-border shadow-sm">**

&#x20;           **<img src="https://images.unsplash.com/photo-1524178232363-1fb28f74b0cd?q=80\&w=400\&auto=format\&fit=crop" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" alt="Related">**

&#x20;         **</div>**

&#x20;         **<h4 class="font-bold text-base leading-snug group-hover:text-primary transition-colors">আন্তর্জাতিক শিক্ষার্থীদের জন্য নতুন স্কলারশিপের সুযোগ</h4>**

&#x20;         **<p class="text-\[10px] text-muted-foreground mt-3 font-bold uppercase tracking-widest flex items-center gap-2">**

&#x20;           **<span class="text-primary">স্কলারশিপ</span> • ৪ দিন আগে**

&#x20;         **</p>**

&#x20;       **</div>**

&#x20;     **</div>**

&#x20;   **</section>**

&#x20; **</main>**



&#x20; **<!-- Footer -->**

&#x20; **<footer class="bg-secondary text-secondary-foreground pt-16 pb-8 border-t border-white/10">**

&#x20;   **<div class="max-w-7xl mx-auto px-4 text-center">**

&#x20;     **<div class="flex flex-col items-center gap-6 mb-10">**

&#x20;       **<div class="bg-primary p-3 rounded-xl shadow-lg shadow-primary/20">**

&#x20;         **<iconify-icon icon="lucide:sun" class="text-4xl text-white"></iconify-icon>**

&#x20;       **</div>**

&#x20;       **<div class="space-y-1">**

&#x20;         **<h2 class="text-3xl font-heading font-bold tracking-tight">THE RISING <span class="text-primary">CAMPUS</span></h2>**

&#x20;         **<p class="text-sm font-bold text-primary/80 uppercase tracking-\[0.3em]">দ্য রাইজিং ক্যাম্পাস</p>**

&#x20;       **</div>**

&#x20;     **</div>**

&#x20;     **<div class="flex flex-wrap justify-center gap-8 mb-10 text-\[10px] font-bold uppercase tracking-widest text-muted-foreground">**

&#x20;       **<a href="#" class="hover:text-primary transition-colors">আমাদের সম্পর্কে</a>**

&#x20;       **<a href="#" class="hover:text-primary transition-colors">যোগাযোগ</a>**

&#x20;       **<a href="#" class="hover:text-primary transition-colors">গোপনীয়তা নীতি</a>**

&#x20;       **<a href="#" class="hover:text-primary transition-colors">বিজ্ঞাপন</a>**

&#x20;       **<a href="#" class="hover:text-primary transition-colors">আর্কাইভ</a>**

&#x20;     **</div>**

&#x20;     **<p class="text-muted-foreground text-\[10px] font-bold uppercase tracking-\[0.2em] pt-8 border-t border-white/5">© ২০২৪ দ্য রাইজিং ক্যাম্পাস • সত্যের সন্ধানে নির্ভীক • সরকারি নিবন্ধন নং: ১২৩৪৫/এবিসি</p>**

&#x20;   **</div>**

&#x20; **</footer>**



&#x20; **<!-- Mobile Bottom Nav -->**

&#x20; **<nav class="md:hidden fixed bottom-0 left-0 right-0 bg-white border-t border-border z-50 px-6 py-3 shadow-\[0\_-4px\_12px\_rgba(0,0,0,0.05)]">**

&#x20;   **<ul class="flex justify-between items-center">**

&#x20;     **<li class="flex flex-col items-center gap-1 text-muted-foreground">**

&#x20;       **<iconify-icon icon="lucide:house" class="text-xl"></iconify-icon>**

&#x20;       **<span class="text-\[10px] font-bold">প্রচ্ছদ</span>**

&#x20;     **</li>**

&#x20;     **<li class="flex flex-col items-center gap-1 text-primary">**

&#x20;       **<iconify-icon icon="lucide:book-open" class="text-xl"></iconify-icon>**

&#x20;       **<span class="text-\[10px] font-bold">পাঠ করছেন</span>**

&#x20;     **</li>**

&#x20;     **<li class="flex flex-col items-center gap-1 text-muted-foreground">**

&#x20;       **<div class="w-12 h-12 bg-primary rounded-full flex items-center justify-center -mt-8 shadow-lg shadow-primary/30 border-4 border-white">**

&#x20;         **<iconify-icon icon="lucide:share-2" class="text-2xl text-white"></iconify-icon>**

&#x20;       **</div>**

&#x20;       **<span class="text-\[10px] font-bold mt-1">শেয়ার</span>**

&#x20;     **</li>**

&#x20;     **<li class="flex flex-col items-center gap-1 text-muted-foreground">**

&#x20;       **<iconify-icon icon="lucide:bookmark" class="text-xl"></iconify-icon>**

&#x20;       **<span class="text-\[10px] font-bold">সংরক্ষণ</span>**

&#x20;     **</li>**

&#x20;     **<li class="flex flex-col items-center gap-1 text-muted-foreground">**

&#x20;       **<iconify-icon icon="lucide:message-circle" class="text-xl"></iconify-icon>**

&#x20;       **<span class="text-\[10px] font-bold">মন্তব্য</span>**

&#x20;     **</li>**

&#x20;   **</ul>**

&#x20; **</nav>**

**</div>**

**</body></html>**

