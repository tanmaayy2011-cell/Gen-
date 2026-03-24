<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NeuralFlow - AI-Powered Workflow Automation</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/lucide@latest"></script>
  <link rel="preconnect" href="https://images.unsplash.com">
  <style>
    html { scroll-behavior: smooth; }
    .gradient-bg { background: linear-gradient(135deg, #6366F1 0%, #3B82F6 100%); }
    .nav-scrolled { @apply bg-black/90 backdrop-blur-xl border-b border-gray-900/50; }
    .card-hover { @apply hover:scale-[1.02] hover:shadow-2xl transition-all duration-200 ease-out; }
  </style>
</head>
<body class="bg-gray-900 text-white overflow-x-hidden">
  <!-- Navigation -->
  <nav id="nav" class="fixed top-0 left-0 right-0 h-16 z-50 transition-all duration-300 ease-out">
    <div class="max-w-7xl mx-auto px-6 h-full flex items-center justify-between">
      <!-- Logo -->
      <div class="text-xl md:text-2xl font-medium text-white tracking-tight">NeuralFlow</div>
      
      <!-- Desktop Links -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#features" class="text-gray-400 hover:text-white transition-colors duration-200 font-medium">Features</a>
        <a href="#pricing" class="text-gray-400 hover:text-white transition-colors duration-200 font-medium">Pricing</a>
        <a href="#docs" class="text-gray-400 hover:text-white transition-colors duration-200 font-medium">Docs</a>
        <a href="#blog" class="text-gray-400 hover:text-white transition-colors duration-200 font-medium">Blog</a>
      </div>

      <!-- CTA Buttons -->
      <div class="flex items-center space-x-4">
        <button class="text-gray-400 hover:text-white px-4 py-2 rounded-lg transition-colors duration-200 font-medium">Sign In</button>
        <button class="bg-white text-black px-6 py-2 rounded-full font-semibold hover:bg-gray-100 transition-all duration-200 shadow-lg">Get Started</button>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="min-h-screen flex items-center justify-center pt-16 pb-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <!-- Beta Badge -->
      <div class="inline-flex items-center px-4 py-1.5 bg-black/50 border border-blue-500/30 rounded-full mb-8 backdrop-blur-sm">
        <span class="text-xs font-medium text-blue-400">Now in Public Beta</span>
      </div>

      <!-- Headline -->
      <h1 class="text-5xl md:text-7xl lg:text-8xl font-medium tracking-tight leading-tight mb-6">
        Automate your workflow
        <span class="block bg-gradient-to-r from-blue-400 to-purple-500 bg-clip-text text-transparent">with AI</span>
      </h1>

      <!-- Subtext -->
      <p class="text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto mb-12 leading-relaxed">
        Build intelligent automations that connect your tools, process data, and take action—all powered by AI.
      </p>

      <!-- CTAs -->
      <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
        <button class="bg-white text-black px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-100 transition-all duration-200 shadow-2xl w-full sm:w-auto">
          <span class="flex items-center justify-center gap-2">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
            Start for Free
          </span>
        </button>
        <button class="border-2 border-gray-700/50 hover:border-gray-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-800/50 backdrop-blur-sm transition-all duration-200 w-full sm:w-auto">
          <span class="flex items-center justify-center gap-2">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path></svg>
            Watch Demo
          </span>
        </button>
      </div>
    </div>

    <!-- Floating Elements -->
    <div class="absolute top-1/2 right-10 hidden xl:block animate-pulse">
      <div class="w-72 h-72 bg-gradient-to-r from-blue-500/20 to-purple-500/20 rounded-full blur-3xl"></div>
    </div>
  </section>

  <!-- Product Preview -->
  <section class="py-32 bg-gradient-to-b from-gray-900/50 to-black">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid md:grid-cols-2 gap-16 items-center">
        <!-- Left Content -->
        <div class="order-2 md:order-1">
          <h2 class="text-4xl md:text-5xl font-medium tracking-tight mb-6">Visual workflow builder</h2>
          <p class="text-xl text-gray-300 mb-8 leading-relaxed max-w-lg">
            Drag & drop interface to build complex automations. Connect 100+ apps with AI-powered actions.
          </p>
          <div class="flex flex-wrap gap-4">
            <span class="inline-flex items-center px-4 py-2 bg-blue-500/10 border border-blue-500/30 rounded-full text-sm font-medium text-blue-400">Visual Builder</span>
            <span class="inline-flex items-center px-4 py-2 bg-purple-500/10 border border-purple-500/30 rounded-full text-sm font-medium text-purple-400">100+ Integrations</span>
          </div>
        </div>

        <!-- Dashboard Mockup -->
        <div class="order-1 md:order-2 relative group">
          <div class="relative bg-gray-800/50 backdrop-blur-xl rounded-3xl p-8 border border-gray-700/50 shadow-2xl card-hover">
            <img 
              src="https://images.unsplash.com/photo-1613428015911-4f57b9e464d5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
              alt="NeuralFlow Dashboard" 
              class="w-full h-[500px] object-cover rounded-2xl shadow-2xl"
            >
            <div class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent rounded-3xl"></div>
            <div class="absolute -top-4 -right-4 w-24 h-24 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl shadow-2xl"></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="py-32">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center mb-24">
        <h2 class="text-4xl md:text-5xl font-medium tracking-tight mb-6">Everything you need to automate</h2>
        <p class="text-xl text-gray-300 max-w-2xl mx-auto">
          Powerful features designed for teams of all sizes
        </p>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Feature 1 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="wand-2" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">Visual Builder</h3>
          <p class="text-gray-300 leading-relaxed">Drag & drop interface to build complex workflows without writing code.</p>
        </div>

        <!-- Feature 2 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="zap" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">100+ Integrations</h3>
          <p class="text-gray-300 leading-relaxed">Connect your entire stack with native integrations for all major tools.</p>
        </div>

        <!-- Feature 3 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="brain" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">AI Actions</h3>
          <p class="text-gray-300 leading-relaxed">Intelligent actions powered by cutting-edge AI models.</p>
        </div>

        <!-- Feature 4 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="activity" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">Real-time Logs</h3>
          <p class="text-gray-300 leading-relaxed">Monitor every execution with detailed logs and debugging tools.</p>
        </div>

        <!-- Feature 5 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="users" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">Team Collaboration</h3>
          <p class="text-gray-300 leading-relaxed">Share workflows, set permissions, and collaborate with your team.</p>
        </div>

        <!-- Feature 6 -->
        <div class="group p-8 bg-gray-800/50 backdrop-blur-xl rounded-2xl border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-500 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-200">
            <i data-lucide="shield" class="w-8 h-8 text-white"></i>
          </div>
          <h3 class="text-2xl font-medium mb-4">Enterprise Security</h3>
          <p class="text-gray-300 leading-relaxed">SOC 2, GDPR compliant with advanced security and compliance features.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Section -->
  <section id="pricing" class="py-32 bg-gradient-to-b from-black to-gray-900/50">
    <div class="max-w-4xl mx-auto px-6">
      <div class="text-center mb-24">
        <h2 class="text-4xl md:text-5xl font-medium tracking-tight mb-6">Simple, transparent pricing</h2>
        <p class="text-xl text-gray-300 max-w-2xl mx-auto">
          Start building for free. Scale as you grow.
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Free Plan -->
        <div class="group relative bg-gray-800/50 backdrop-blur-xl rounded-3xl p-8 border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="absolute -top-6 left-1/2 transform -translate-x-1/2 bg-white text-black px-4 py-2 rounded-full text-sm font-semibold">Most Popular</div>
          <div class="text-center mb-8">
            <h3 class="text-3xl font-medium mb-2">Free</h3>
            <div class="text-4xl font-bold text-white">$0<span class="text-lg font-normal text-gray-400">/mo</span></div>
          </div>
          <ul class="space-y-4 mb-8 text-left">
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>50 workflows</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>10k executions/mo</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>Basic integrations</li>
          </ul>
          <button class="w-full bg-transparent border-2 border-gray-700 hover:border-white px-6 py-4 rounded-2xl font-semibold transition-all duration-200">Get Started</button>
        </div>

        <!-- Pro Plan -->
        <div class="group bg-gradient-to-br from-gray-800/50 to-gray-900/50 backdrop-blur-xl rounded-3xl p-8 border border-blue-500/30 shadow-2xl card-hover relative overflow-hidden">
          <div class="absolute inset-0 bg-gradient-to-r from-blue-500/5 to-purple-500/5"></div>
          <div class="text-center mb-8 relative z-10">
            <h3 class="text-3xl font-medium mb-2">Pro</h3>
            <div class="text-4xl font-bold text-white">$29<span class="text-lg font-normal text-gray-400">/mo</span></div>
          </div>
          <ul class="space-y-4 mb-8 text-left relative z-10">
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>Unlimited workflows</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>1M executions/mo</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>All integrations</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>Team collaboration</li>
          </ul>
          <button class="w-full bg-white text-black border-2 border-white/20 px-6 py-4 rounded-2xl font-semibold hover:bg-gray-100 transition-all duration-200 shadow-2xl relative z-10">Start Pro Trial</button>
        </div>

        <!-- Enterprise Plan -->
        <div class="group bg-gray-800/50 backdrop-blur-xl rounded-3xl p-8 border border-gray-700/50 hover:bg-gray-800/75 card-hover">
          <div class="text-center mb-8">
            <h3 class="text-3xl font-medium mb-2">Enterprise</h3>
            <div class="text-4xl font-bold text-white">Custom</div>
          </div>
          <ul class="space-y-4 mb-8 text-left">
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5 text-green-400 mr-3"></i>Everything in Pro</li>
            <li class="flex items-center"><i data-lucide="check" class="w-5 h-5# Gen-
