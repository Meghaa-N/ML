





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-FG+rXqMOivrAjdEQE7tO4BwM1poGmg70hJFTlNSxjX87grtrZ6UnPR8NkzwUHlQEGviu9XuRYeO8zH9YwvZhdg==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-146fab5ea30e8afac08dd11013bb4ee0.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-xhEwXUnAQrwtzx3SUeDRw7/d7lQmtwNKXic7VeJinUexaePJ2knNKoM3SJzmSmDq/Stn081QrAsZJ8UU98Rw0w==" rel="stylesheet" href="https://github.githubassets.com/assets/github-c611305d49c042bc2dcf1dd251e0d1c3.css" />
    
    
    
    


  <meta name="viewport" content="width=device-width">
  
  <title>numpy-100/100_Numpy_exercises_with_hints_with_solutions.md at master · rougier/numpy-100</title>
    <meta name="description" content="100 numpy exercises (with solutions). Contribute to rougier/numpy-100 development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars1.githubusercontent.com/u/327203?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="rougier/numpy-100" /><meta name="twitter:description" content="100 numpy exercises (with solutions). Contribute to rougier/numpy-100 development by creating an account on GitHub." />
    <meta property="og:image" content="https://avatars1.githubusercontent.com/u/327203?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="rougier/numpy-100" /><meta property="og:url" content="https://github.com/rougier/numpy-100" /><meta property="og:description" content="100 numpy exercises (with solutions). Contribute to rougier/numpy-100 development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NTIxOTk0MjE4OjEyZGE4MDMyNGZmZTNmMjg5MmZhZDc5ZjEyOThkZTczNDg1OWJiOTJkOTRmMWU0YzM1NDExYTkxOTQzZjcyNGM=--6595ebbc8ac789085e730b2bd438d408e7cbd372">
  <link rel="sudo-modal" href="/sessions/sudo_modal">

  <meta name="request-id" content="DFFD:363B:654F94:87DCD1:5EAE9ED3" data-pjax-transient="true" /><meta name="html-safe-nonce" content="49f60db19f5c26f8dcff1f57279d288662e0f0d7" data-pjax-transient="true" /><meta name="visitor-payload" content="eyJyZWZlcnJlciI6Imh0dHBzOi8vZ2l0aHViLmNvbS9yb3VnaWVyL251bXB5LTEwMCIsInJlcXVlc3RfaWQiOiJERkZEOjM2M0I6NjU0Rjk0Ojg3RENEMTo1RUFFOUVEMyIsInZpc2l0b3JfaWQiOiI4NDgzOTUxNTY1MzAzODcyOTAiLCJyZWdpb25fZWRnZSI6ImFwLXNvdXRoLTEiLCJyZWdpb25fcmVuZGVyIjoiaWFkIn0=" data-pjax-transient="true" /><meta name="visitor-hmac" content="516c36d39e3e691896c87ada74576384b0daf90a70fb5c479ae0a294c49a40a8" data-pjax-transient="true" />



  <meta name="github-keyboard-shortcuts" content="repository,source-code" data-pjax-transient="true" />

  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

<meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-actor-id" content="62483513" /><meta name="octolytics-actor-login" content="Meghaa-N" /><meta name="octolytics-actor-hash" content="c22324331ad5cb4889cf0d954cac5a08fd580a0a42acbd3e33d53c70cfc6fe88" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="2e7f128324be376ed4a7ba177412da84">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="Meghaa-N">

      <meta name="expected-hostname" content="github.com">

      <meta name="js-proxy-site-detection-payload" content="ODg3MmM4YmE3NzA1ZDNiOWQ5ZGQwNGNiMGYwYzY5ZWY2NWZlN2M3ZDdhYmYyNWQ3ZTQ3MjFmYjg4YTQ4MDg3OXx7InJlbW90ZV9hZGRyZXNzIjoiMTAzLjU5LjEzNS4xOCIsInJlcXVlc3RfaWQiOiJERkZEOjM2M0I6NjU0Rjk0Ojg3RENEMTo1RUFFOUVEMyIsInRpbWVzdGFtcCI6MTU4ODUwMjIzOCwiaG9zdCI6ImdpdGh1Yi5jb20ifQ==">

    <meta name="enabled-features" content="MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,GHE_CLOUD_TRIAL,PAGE_STALE_CHECK">

  <meta http-equiv="x-pjax-version" content="c4225fc3c5010019067425065faf9eb2">
  

      <link href="https://github.com/rougier/numpy-100/commits/master.atom" rel="alternate" title="Recent Commits to numpy-100:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/rougier/numpy-100 git https://github.com/rougier/numpy-100.git">

  <meta name="octolytics-dimension-user_id" content="327203" /><meta name="octolytics-dimension-user_login" content="rougier" /><meta name="octolytics-dimension-repository_id" content="20206590" /><meta name="octolytics-dimension-repository_nwo" content="rougier/numpy-100" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="20206590" /><meta name="octolytics-dimension-repository_network_root_nwo" content="rougier/numpy-100" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="alternate icon" class="js-site-favicon" type="image/png" href="https://github.githubassets.com/favicons/favicon.png">
  <link rel="icon" class="js-site-favicon" type="image/svg+xml" href="https://github.githubassets.com/favicons/favicon.svg">

<meta name="theme-color" content="#1e2327">


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

    <div class="position-relative js-header-wrapper ">
      <a href="#start-of-content" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
      <span class="Progress progress-pjax-loader position-fixed width-full js-pjax-loader-bar">
        <span class="progress-pjax-loader-bar top-0 left-0" style="width: 0%;"></span>
      </span>

      
      



          <header class="Header py-lg-0 js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">
  <div class="Header-item d-none d-lg-flex">
    <a class="Header-link" href="https://github.com/" data-hotkey="g d"
  aria-label="Homepage " data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>

  </div>

  <div class="Header-item d-lg-none">
    <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
      <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"></path></svg>
    </button>
  </div>

  <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
      <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="20206590" data-scoped-search-url="/rougier/numpy-100/search" data-unscoped-search-url="/search" action="/rougier/numpy-100/search" accept-charset="UTF-8" method="get">
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations"
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" value="UhOoAH2dCgMKhWbHAFQv0A1NWGJmEOKtSBaPNN1Iq0WRL+uYjQe4xYCFG/45Sth5rzIdbU8lLno02Moawe+Ufg==" data-csrf="true" class="js-data-jump-to-suggestions-path-csrf" />
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"></path></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"></path></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 00-1 1v14a1 1 0 001 1h13a1 1 0 001-1V1a1 1 0 00-1-1z"></path></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0013 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 000-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"></path></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


    <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link py-lg-3 d-block d-lg-none py-2 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link py-lg-3  mr-0 mr-lg-3 py-2 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link py-lg-3  mr-0 mr-lg-3 py-2 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>

    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link py-lg-3 d-inline-block" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link py-lg-3  mr-0 mr-lg-3 py-2 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-3 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/Meghaa-N">
      <img class="avatar avatar-user" height="20" width="20" alt="@Meghaa-N" src="https://avatars1.githubusercontent.com/u/62483513?s=60&amp;v=4" />
      Meghaa-N
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="OH+EotF8k90x/AAylIUe8zyeLgBTF/xaXrMl3iaNVN/AMGYhQzkCqnzEIngySlWl1i9MXRg4eipPzaGkMLrxZg==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-3 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 17" version="1.1" width="16" height="17" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"></path></svg>
        Sign out
      </button>
</form></nav>

  </div>

  <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
    <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
                <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
    <a class="Header-link" href="/rougier">rougier</a>
    /
    <a class="Header-link" href="/rougier/numpy-100">numpy-100</a>

</div>
  </div>

  <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
    
    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-sw js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:62483513" href="/notifications">
        <span class="js-indicator-modifier mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"></path></svg>
</a>
  </div>


  <div class="Header-item position-relative d-none d-lg-flex">
    <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"></path></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-n2">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>


  <div role="none" class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="rougier/numpy-100">This repository</span>
  </div>
    <a role="menuitem" class="dropdown-item" href="/rougier/numpy-100/issues/new/choose" data-ga-click="Header, create new issue" data-skip-pjax>
      New issue
    </a>


  </details-menu>
</details>

  </div>

  <div class="Header-item position-relative mr-0 d-none d-lg-flex">
    
  <details class="details-overlay details-reset js-feature-preview-indicator-container" data-feature-preview-indicator-src="/users/Meghaa-N/feature_preview/indicator_check">

  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img
  alt="@Meghaa-N"
  width="20"
  height="20"
  src="https://avatars1.githubusercontent.com/u/62483513?s=60&amp;v=4"
  class="avatar avatar-user " />

      <span class="feature-preview-indicator js-feature-preview-indicator" style="top: 10px;" hidden></span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-n2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/Meghaa-N" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">Meghaa-N</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:327203,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:62483513,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;}}" data-hydro-click-hmac="fa6ed23760d1ca5ce09888868b78299b5736a0f99ae5e4ebab2d5794715af797">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"></path></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="poY8teKo2qVrF5C9q3s7XJ0/vxS5QsN1YB1VLbOiQ1z7RWAn3j+BW8QEaXY/hAf4f82aYm4LywlUB8Uhn9z+HA==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 01-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 01-1.45-2.17A6.59 6.59 0 011.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 018 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"></path></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
          <div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2020-05-03T16:37:18+05:30">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2020-05-03T17:07:18+05:30">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2020-05-03T20:07:18+05:30">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2020-05-03T23:59:59+05:30">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2020-05-03T23:59:59+05:30">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>

    <a role="menuitem" class="dropdown-item" href="/Meghaa-N" data-ga-click="Header, go to profile, text:your profile">Your profile</a>

    <a role="menuitem" class="dropdown-item" href="/Meghaa-N?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/Meghaa-N?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/Meghaa-N?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>





    <div role="none" class="dropdown-divider"></div>
      
<div id="feature-enrollment-toggle" class="hide-sm hide-md feature-preview-details position-relative">
  <button
    type="button"
    class="dropdown-item btn-link"
    role="menuitem"
    data-feature-preview-trigger-url="/users/Meghaa-N/feature_previews"
    data-feature-preview-close-details="{&quot;event_type&quot;:&quot;feature_preview.clicks.close_modal&quot;,&quot;payload&quot;:{&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}"
    data-feature-preview-close-hmac="7ddeb3e6ff199ed593bfd3b203935ab85c1c08e85502936dc67dea148d9dcd55"
    data-hydro-click="{&quot;event_type&quot;:&quot;feature_preview.clicks.open_modal&quot;,&quot;payload&quot;:{&quot;link_location&quot;:&quot;user_dropdown&quot;,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}"
    data-hydro-click-hmac="846b0c7b5a1bc7bcd3ffc38ce3285f1bdc0cc095b2c5ba71c171116fcd39ea65"
  >
    Feature preview
  </button>
    <span class="feature-preview-indicator js-feature-preview-indicator" hidden></span>
</div>

    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="sUr6jJ6B0Ce4kj9izBAewUeOtMrH+cfjSD6upXEhKchJBRgPDMRBUPWqHShq31WXrT/Wl4zWQZNZQCrfZxaMcQ==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
      <input type="text" name="required_field_98ef" hidden="hidden" class="form-control" /><input type="hidden" name="timestamp" value="1588502238516" class="form-control" /><input type="hidden" name="timestamp_secret" value="d2d3c240ebdb8db93304760c1b7cb00607d6adc2e3dc5538dc08791a9ae4d4ca" class="form-control" />
</form>  </details-menu>
</details>

  </div>

</header>

        

    </div>

  <div id="start-of-content" class="show-on-focus"></div>




    <div id="js-flash-container">


  <template class="js-flash-template">
    <div class="flash flash-full  js-flash-template-container">
  <div class="container-lg px-2" >
    <button class="flash-close js-flash-close" type="button" aria-label="Dismiss this message">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
    </button>
    
      <div class="js-flash-template-message"></div>

  </div>
</div>
  </template>
</div>


      

  <include-fragment class="js-notification-shelf-include-fragment" data-base-src="https://github.com/notifications/beta/shelf"></include-fragment>




  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      

  


      <div class="border-bottom shelf intro-shelf js-notice mb-0 pb-4">
  <div class="width-full container">
    <div class="width-full mx-auto shelf-content">
      <h2 class="shelf-title">Learn Git and GitHub without any code!</h2>
      <p class="shelf-lead">
          Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.
      </p>
      <a class="btn btn-primary shelf-cta" target="_blank" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;READ_GUIDE&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="96491a66b481baff58ecae77b9998b0d121a4d3f47797088fb20d56f3bb19b8c" href="https://guides.github.com/activities/hello-world/">Read the guide</a>
    </div>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="shelf-dismiss js-notice-dismiss" action="/dashboard/dismiss_bootcamp" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="oPI86a5LkBhdQot7xcxXFLdi+hG9Q2EbobDmc5ZJonMiuupsdnN/G360149k+kpgxLY6n8qALZ8eY8RFg/bpVA==" />
      <button name="button" type="submit" class="mr-1 close-button tooltipped tooltipped-w" aria-label="Hide this notice forever" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;DISMISS_BANNER&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="ac593ae97a4772df7b2de909fa1da661a135ad79e228a6f2cbd41e7b9acb6230">
        <svg aria-label="Hide this notice forever" class="octicon octicon-x v-align-text-top" viewBox="0 0 12 16" version="1.1" width="12" height="16" role="img"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
</button></form>  </div>
</div>










  <div class="pagehead repohead hx_repohead readability-menu bg-gray-light pb-0 pt-0 pt-lg-3">

    <div class="d-flex container-lg mb-4 p-responsive d-none d-lg-flex">

      <div class="flex-auto min-width-0 width-fit mr-3">
        <h1 class="public  d-flex flex-wrap flex-items-center break-word float-none ">
  <span class="flex-self-stretch" style="margin-top: -2px;">
      <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
  </span>
  <span class="author ml-2 flex-self-stretch" itemprop="author">
    <a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/users/rougier/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rougier">rougier</a>
  </span>
  <span class="path-divider flex-self-stretch">/</span>
  <strong itemprop="name" class="mr-2 flex-self-stretch">
    <a data-pjax="#js-repo-pjax-container" href="/rougier/numpy-100">numpy-100</a>
  </strong>
  
</h1>


      </div>

      <ul class="pagehead-actions flex-shrink-0 " >

    <li>
      <details id="funding-links-modal" class="details-reset details-overlay details-overlay-dark d-inline-block float-left" >
        <summary id="sponsor-button-repo" class="btn btn-sm"
          title="Sponsor rougier/numpy-100"
          data-ga-click="Repository, show sponsor modal, action:blob#show; text:Sponsor"
          >
          <svg class="octicon octicon-heart text-pink v-align-text-bottom" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.727 3C7.091 3 6.001 4.65 6.001 4.65S4.909 3 3.273 3C1.636 3 0 4.1 0 6.3 0 9.6 6 14 6 14s6-4.4 6-7.7C12 4.1 10.364 3 8.727 3z"></path></svg>
          Sponsor
        </summary>
        <details-dialog
          class="anim-fade-in fast Box Box--overlay d-flex flex-column"
            src="/rougier/numpy-100/funding_links?fragment=1"
            preload
          >
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
            </button>
            <h3 class="Box-title">
              Sponsor rougier/numpy-100
            </h3>
          </div>
          <div class="overflow-auto">
            <include-fragment
              >
              <div class="octocat-spinner my-3" aria-label="Loading..."></div>
            </include-fragment>
          </div>
        </details-dialog>
      </details>
    </li>



  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="LoOS4uwcxRbGPRyB3xmRxX1/EeAj6l3rKNAbyZBTfLxBGDnQIk1eA0cNvyzQychn6Ad1u6oub34W2cMGSnCZmQ==" />      <input type="hidden" name="repository_id" value="20206590">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="92db77a31c13a69ccf63ab2dfc7120d4706b1d30025a253a29ab268a6e809bae" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"></path></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"></path></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"></path></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"></path></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"></path></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/rougier/numpy-100/watchers"
          aria-label="168 users are watching this repository">
          168
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <form class="starred js-social-form" action="/rougier/numpy-100/unstar" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="O4Gm/L9ZkemAyGPke068nSgCnhL3y2UzTTgfOixPabs7t+pNJdqfaI+WOm2omVzGO1dlNepRg+8FGY1GdEDapw==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar rougier/numpy-100" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="db6027ac67e3eb921b1b72ab12286008faaeb272c08bf0cd5f9e8230b48f274b" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg height="16" class="octicon octicon-star v-align-text-bottom" vertical_align="text_bottom" viewBox="0 0 14 16" version="1.1" width="14" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"></path></svg>

        Unstar
</button>        <a class="social-count js-social-count" href="/rougier/numpy-100/stargazers"
           aria-label="5120 users starred this repository">
           5.1k
        </a>
</form>
    <form class="unstarred js-social-form" action="/rougier/numpy-100/star" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="vt90cORZj/b+RlsouXzeqxhY4dyvYmP8LD+xdCEx2BANnDM+Rqk4XyAMZq0jJXwZ1VKeeXMVBmO4WiwZDTUmAQ==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star rougier/numpy-100" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="254f80a537b76e130f72691ee60d03c33f03f638130b7f6b61a8e28be53e9224" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg height="16" class="octicon octicon-star v-align-text-bottom" vertical_align="text_bottom" viewBox="0 0 14 16" version="1.1" width="14" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"></path></svg>

        Star
</button>        <a class="social-count js-social-count" href="/rougier/numpy-100/stargazers"
           aria-label="5120 users starred this repository">
          5.1k
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="btn-with-count" action="/rougier/numpy-100/fork" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="am2k8jGTNBYd94ut0ndfWo/q9DmKvSd/OeqNtdLwvCvWMJaIu/WqyW0TqsnhsDApqoUA9CMsyo7BSi9feDMiWg==" />
            <button class="btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:20206590,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="b33e873f767c23b553967323b385fadace7364663c141706914222521789b815" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" type="submit" title="Fork your own copy of rougier/numpy-100 to your account" aria-label="Fork your own copy of rougier/numpy-100 to your account">              <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 00-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 002 1a1.993 1.993 0 00-1 3.72V6.5l3 3v1.78A1.993 1.993 0 005 15a1.993 1.993 0 001-3.72V9.5l3-3V4.72A1.993 1.993 0 008 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
              Fork
</button></form>
    <a href="/rougier/numpy-100/network/members" class="social-count"
       aria-label="2611 users forked this repository">
      2.6k
    </a>
  </li>
</ul>

    </div>
      <nav class="js-repo-nav js-sidenav-container-pjax clearfix hx_reponav reponav p-responsive d-none d-lg-block container-lg"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">
  <ul class="list-style-none">
    <li  itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /rougier/numpy-100" href="/rougier/numpy-100">
        <div class="d-inline"><svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg></div>
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </li>

      <li  itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /rougier/numpy-100/issues" href="/rougier/numpy-100/issues">
          <div class="d-inline"><svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 011.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"></path></svg></div>
          <span itemprop="name">Issues</span>
          <span class="Counter">16</span>
          <meta itemprop="position" content="2">
</a>      </li>

    <li  itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a data-hotkey="g p" data-skip-pjax="true" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /rougier/numpy-100/pulls" href="/rougier/numpy-100/pulls">
        <div class="d-inline"><svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0010 15a1.993 1.993 0 001-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v6.56A1.993 1.993 0 002 15a1.993 1.993 0 001-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg></div>
        <span itemprop="name">Pull requests</span>
        <span class="Counter">11</span>
        <meta itemprop="position" content="4">
</a>    </li>


      <li itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement" class="position-relative float-left ">
        <a data-hotkey="g w" data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /rougier/numpy-100/actions" href="/rougier/numpy-100/actions">
          <div class="d-inline"><svg class="octicon octicon-play" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8A7 7 0 110 8a7 7 0 0114 0zm-8.223 3.482l4.599-3.066a.5.5 0 000-.832L5.777 4.518A.5.5 0 005 4.934v6.132a.5.5 0 00.777.416z"></path></svg></div>
          Actions
</a>
      </li>


      <li >
        <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /rougier/numpy-100/wiki" href="/rougier/numpy-100/wiki">
          <div class="d-inline"><svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"></path></svg></div>
          Wiki
</a>      </li>

      <li >
        <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security overview alerts policy token_scanning code_scanning /rougier/numpy-100/security" href="/rougier/numpy-100/security">
          <div class="d-inline"><svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"></path></svg></div>
          Security
              <span class="Counter js-security-tab-count" data-url="/rougier/numpy-100/security/overall-count" hidden></span>
</a>      </li>

      <li >
        <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph dependabot_updates pulse people /rougier/numpy-100/pulse" href="/rougier/numpy-100/pulse">
          <div class="d-inline"><svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"></path></svg></div>
          Insights
</a>      </li>


  </ul>
</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /rougier/numpy-100" href="/rougier/numpy-100">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /rougier/numpy-100/issues" href="/rougier/numpy-100/issues">
          <span itemprop="name">Issues</span>
          <span class="Counter">16</span>
          <meta itemprop="position" content="2">
</a>      </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /rougier/numpy-100/pulls" href="/rougier/numpy-100/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">11</span>
        <meta itemprop="position" content="4">
</a>    </span>



      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_actions /rougier/numpy-100/actions" href="/rougier/numpy-100/actions">
          <span itemprop="name">Actions</span>
          <meta itemprop="position" content="6">
</a>      </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_wiki /rougier/numpy-100/wiki" href="/rougier/numpy-100/wiki">
          <span itemprop="name">Wiki</span>
          <meta itemprop="position" content="7">
</a>      </span>

      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security overview alerts policy token_scanning code_scanning /rougier/numpy-100/security" href="/rougier/numpy-100/security">
        <span itemprop="name">Security</span>
            <span class="Counter js-security-deferred-tab-count" hidden></span>
        <meta itemprop="position" content="8">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /rougier/numpy-100/pulse" href="/rougier/numpy-100/pulse">
        Pulse
</a>
      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="community /rougier/numpy-100/community" href="/rougier/numpy-100/community">
          Community
</a>      </span>

  </nav>
</div>


  </div>

  

  <include-fragment class="js-notification-shelf-include-fragment" data-base-src="https://github.com/notifications/beta/shelf"></include-fragment>


<div class="container-lg clearfix new-discussion-timeline  p-responsive">
  <div class="repository-content ">

    
    

  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/rougier/numpy-100/blob/69109eeba557401e05970f724b2485af26f7a955/100_Numpy_exercises_with_hints_with_solutions.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v22:0a87f1751d26bf068f148f948d4a0852 -->
    

    <div class="d-flex flex-items-start flex-shrink-0 flex-column flex-md-row pb-3">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay branch-select-menu " id="branch-select-menu">
  <summary class="btn css-truncate btn-sm"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
    <span class="dropdown-caret"></span>
  </summary>

  <details-menu class="SelectMenu SelectMenu--hasFilter" src="/rougier/numpy-100/refs/master/100_Numpy_exercises_with_hints_with_solutions.md?source_action=show&amp;source_controller=blob" preload>
    <div class="SelectMenu-modal">
      <include-fragment class="SelectMenu-loading" aria-label="Menu is loading">
        <svg class="octicon octicon-octoface anim-pulse" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"></path></svg>
      </include-fragment>
    </div>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/rougier/numpy-100/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="100_Numpy_exercises_with_hints_with_solutions.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment d-inline-block wb-break-all"><a data-pjax="true" href="/rougier/numpy-100"><span>numpy-100</span></a></span></span><span class="separator">/</span><strong class="final-path">100_Numpy_exercises_with_hints_with_solutions.md</strong>
          <span class="separator">/</span><details class="details-reset details-overlay d-inline" id="jumpto-symbol-select-menu">
  <summary class="btn-link link-gray css-truncate" aria-haspopup="true" data-hotkey="r" data-hydro-click="{&quot;event_type&quot;:&quot;code_navigation.click_on_blob_definitions&quot;,&quot;payload&quot;:{&quot;action&quot;:&quot;click_on_blob_definitions&quot;,&quot;repository_id&quot;:20206590,&quot;ref&quot;:&quot;master&quot;,&quot;language&quot;:&quot;Python&quot;,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}" data-hydro-click-hmac="1712c3d757b6d0aeef9d20b3593dcecf48ba9b2535fee65ae40b19bb7227c732">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg>
    <span data-menu-button>Jump to</span>
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="SelectMenu SelectMenu--hasFilter" role="menu">
    <div class="SelectMenu-modal">
      <header class="SelectMenu-header">
        <span class="SelectMenu-title">Code definitions</span>
        <button class="SelectMenu-closeButton" type="button" data-toggle-for="jumpto-symbol-select-menu">
          <svg aria-label="Close menu" class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" role="img"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
        </button>
      </header>
        <div class="SelectMenu-filter">
          <input
            class="SelectMenu-input form-control js-filterable-field"
            id="jumpto-symbols-filter-field"
            type="text"
            autocomplete="off"
            spellcheck="false"
            autofocus
            placeholder="Filter definitions"
            aria-label="Filter definitions">
        </div>
      <div class="SelectMenu-list">
        <div data-filterable-for="jumpto-symbols-filter-field" data-filterable-type="substring">
        </div>
      </div>
      <footer class="SelectMenu-footer">
        <div class="d-flex flex-justify-between">
          Code navigation index up-to-date
          <svg class="octicon octicon-primitive-dot text-green" viewBox="0 0 8 16" version="1.1" width="8" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 8c0-2.2 1.8-4 4-4s4 1.8 4 4-1.8 4-4 4-4-1.8-4-4z"></path></svg>
        </div>
      </footer>
    </div>
  </details-menu>
</details>

      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/rougier/numpy-100/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="100_Numpy_exercises_with_hints_with_solutions.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0 mb-3">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <img class="avatar" width="20" height="20" alt="" src="https://camo.githubusercontent.com/48730084197adb1a650673315734e9ccbafe7b05/68747470733a2f2f322e67726176617461722e636f6d2f6176617461722f35363538666663636565376630656266646132623232363233386231656236653f643d68747470732533412532462532466769746875622e6769746875626173736574732e636f6d253246696d6167657325324667726176617461727325324667726176617461722d757365722d3432302e706e6726723d6726733d313430" data-canonical-src="https://2.gravatar.com/avatar/5658ffccee7f0ebfda2b226238b1eb6e?d=https%3A%2F%2Fgithub.githubassets.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=g&amp;s=140" />
          <span class="text-bold link-gray-dark lh-default v-align-middle">Your Name</span>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="fix No.25" class="link-gray" href="/rougier/numpy-100/commit/c7cf6fd5f3e72d5e2619e88022b0a9610e239b40">fix No.25</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/rougier/numpy-100/commit/c7cf6fd5f3e72d5e2619e88022b0a9610e239b40" data-pjax>c7cf6fd</a>
          <relative-time datetime="2020-02-12T10:09:05Z" class="no-wrap">Feb 12, 2020</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link">
          <span><strong>2</strong> contributors</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          src="/rougier/numpy-100/contributors-list/master/100_Numpy_exercises_with_hints_with_solutions.md" preload>
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
          <include-fragment class="octocat-spinner my-3" aria-label="Loading..."></include-fragment>
        </details-dialog>
      </details>
        <span class="">
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/SebastianoF/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rougier/numpy-100/commits/master/100_Numpy_exercises_with_hints_with_solutions.md?author=SebastianoF">
      <img class="avatar mr-1 avatar-user" src="https://avatars0.githubusercontent.com/u/8709755?s=40&amp;v=4" width="20" height="20" alt="@SebastianoF" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/username12/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rougier/numpy-100/commits/master/100_Numpy_exercises_with_hints_with_solutions.md?author=username12">
      <img class="avatar mr-1 avatar-user" src="https://avatars3.githubusercontent.com/u/1708813?s=40&amp;v=4" width="20" height="20" alt="@username12" /> 
</a>
</span>

    </div>
  </div>






    <div class="Box mt-3 position-relative
      ">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">
  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">

      1174 lines (982 sloc)
      <span class="file-info-divider"></span>
    29.3 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/rougier/numpy-100/raw/master/100_Numpy_exercises_with_hints_with_solutions.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/rougier/numpy-100/blame/master/100_Numpy_exercises_with_hints_with_solutions.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/rougier/numpy-100/commits/master/100_Numpy_exercises_with_hints_with_solutions.md">History</a>
    </div>


    <div>
          <a class="btn-octicon tooltipped tooltipped-nw js-remove-unless-platform"
             data-platforms="windows,mac"
             href="https://desktop.github.com"
             aria-label="Open this file in GitHub Desktop"
             data-ga-click="Repository, open with desktop">
              <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"></path></svg>
          </a>

          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/rougier/numpy-100/edit/master/100_Numpy_exercises_with_hints_with_solutions.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="uDbzJzQ4kvv6IZYXnqQWNUeczdgNPGOUg242SVTyBy989PGuhYcTZfIsBSJwkfD6QXeF8iHDKyL4oRfKGoQe+Q==" />
            <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
              <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 011.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg>
            </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/rougier/numpy-100/delete/master/100_Numpy_exercises_with_hints_with_solutions.md" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="BL0lQIH+aDuULC1IPvspDxtFPoL4bf/HZQOi+noNXlMvGjoPX+yiWZKu4Jz4D88VVSabqaK1HJkpOV99kuCkQg==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Fork this project and delete the file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"></path></svg>
            </button>
</form>    </div>
  </div>
</div>



      
  <div id="readme" class="Box-body readme blob js-code-block-container px-5">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-100-numpy-exercises" class="anchor" aria-hidden="true" href="#100-numpy-exercises"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>100 numpy exercises</h1>
<p>This is a collection of exercises that have been collected in the numpy mailing list, on stack overflow
and in the numpy documentation. The goal of this collection is to offer a quick reference for both old
and new users but also to provide a set of exercises for those who teach.</p>
<p>If you find an error or think you've a better way to solve some of them, feel
free to open an issue at <a href="https://github.com/rougier/numpy-100">https://github.com/rougier/numpy-100</a>.
File automatically generated. See the documentation to update questions/answers/hints programmatically.</p>
<h4><a id="user-content-1-import-the-numpy-package-under-the-name-np-" class="anchor" aria-hidden="true" href="#1-import-the-numpy-package-under-the-name-np-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1. Import the numpy package under the name <code>np</code> (★☆☆)</h4>
<p><code>hint: import … as</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span></pre></div>
<h4><a id="user-content-2-print-the-numpy-version-and-the-configuration-" class="anchor" aria-hidden="true" href="#2-print-the-numpy-version-and-the-configuration-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2. Print the numpy version and the configuration (★☆☆)</h4>
<p><code>hint: np.__version__, np.show_config)</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">__version__</span>)
<span class="pl-s1">np</span>.<span class="pl-en">show_config</span>()</pre></div>
<h4><a id="user-content-3-create-a-null-vector-of-size-10-" class="anchor" aria-hidden="true" href="#3-create-a-null-vector-of-size-10-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3. Create a null vector of size 10 (★☆☆)</h4>
<p><code>hint: np.zeros</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>(<span class="pl-c1">10</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-4-how-to-find-the-memory-size-of-any-array-" class="anchor" aria-hidden="true" href="#4-how-to-find-the-memory-size-of-any-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4. How to find the memory size of any array (★☆☆)</h4>
<p><code>hint: size, itemsize</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-en">print</span>(<span class="pl-s">"%d bytes"</span> <span class="pl-c1">%</span> (<span class="pl-v">Z</span>.<span class="pl-s1">size</span> <span class="pl-c1">*</span> <span class="pl-v">Z</span>.<span class="pl-s1">itemsize</span>))</pre></div>
<h4><a id="user-content-5-how-to-get-the-documentation-of-the-numpy-add-function-from-the-command-line-" class="anchor" aria-hidden="true" href="#5-how-to-get-the-documentation-of-the-numpy-add-function-from-the-command-line-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5. How to get the documentation of the numpy add function from the command line? (★☆☆)</h4>
<p><code>hint: np.info</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c1">%</span><span class="pl-s1">run</span> <span class="pl-s">`python -c "import numpy; numpy.info(numpy.add)"`</span></pre></div>
<h4><a id="user-content-6-create-a-null-vector-of-size-10-but-the-fifth-value-which-is-1-" class="anchor" aria-hidden="true" href="#6-create-a-null-vector-of-size-10-but-the-fifth-value-which-is-1-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>6. Create a null vector of size 10 but the fifth value which is 1 (★☆☆)</h4>
<p><code>hint: array[4]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>(<span class="pl-c1">10</span>)
<span class="pl-v">Z</span>[<span class="pl-c1">4</span>] <span class="pl-c1">=</span> <span class="pl-c1">1</span>
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-7-create-a-vector-with-values-ranging-from-10-to-49-" class="anchor" aria-hidden="true" href="#7-create-a-vector-with-values-ranging-from-10-to-49-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>7. Create a vector with values ranging from 10 to 49 (★☆☆)</h4>
<p><code>hint: arange</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">10</span>,<span class="pl-c1">50</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-8-reverse-a-vector-first-element-becomes-last-" class="anchor" aria-hidden="true" href="#8-reverse-a-vector-first-element-becomes-last-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>8. Reverse a vector (first element becomes last) (★☆☆)</h4>
<p><code>hint: array[::-1]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">50</span>)
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>[::<span class="pl-c1">-</span><span class="pl-c1">1</span>]
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-9-create-a-3x3-matrix-with-values-ranging-from-0-to-8-" class="anchor" aria-hidden="true" href="#9-create-a-3x3-matrix-with-values-ranging-from-0-to-8-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>9. Create a 3x3 matrix with values ranging from 0 to 8 (★☆☆)</h4>
<p><code>hint: reshape</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">nz</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">nonzero</span>([<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">0</span>,<span class="pl-c1">0</span>,<span class="pl-c1">4</span>,<span class="pl-c1">0</span>])
<span class="pl-en">print</span>(<span class="pl-s1">nz</span>)</pre></div>
<h4><a id="user-content-10-find-indices-of-non-zero-elements-from-120040-" class="anchor" aria-hidden="true" href="#10-find-indices-of-non-zero-elements-from-120040-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>10. Find indices of non-zero elements from [1,2,0,0,4,0] (★☆☆)</h4>
<p><code>hint: np.nonzero</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">nz</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">nonzero</span>([<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">0</span>,<span class="pl-c1">0</span>,<span class="pl-c1">4</span>,<span class="pl-c1">0</span>])
<span class="pl-en">print</span>(<span class="pl-s1">nz</span>)</pre></div>
<h4><a id="user-content-11-create-a-3x3-identity-matrix-" class="anchor" aria-hidden="true" href="#11-create-a-3x3-identity-matrix-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>11. Create a 3x3 identity matrix (★☆☆)</h4>
<p><code>hint: np.eye</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">eye</span>(<span class="pl-c1">3</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-12-create-a-3x3x3-array-with-random-values-" class="anchor" aria-hidden="true" href="#12-create-a-3x3x3-array-with-random-values-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>12. Create a 3x3x3 array with random values (★☆☆)</h4>
<p><code>hint: np.random.random</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">3</span>,<span class="pl-c1">3</span>,<span class="pl-c1">3</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-13-create-a-10x10-array-with-random-values-and-find-the-minimum-and-maximum-values-" class="anchor" aria-hidden="true" href="#13-create-a-10x10-array-with-random-values-and-find-the-minimum-and-maximum-values-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>13. Create a 10x10 array with random values and find the minimum and maximum values (★☆☆)</h4>
<p><code>hint: min, max</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-v">Zmin</span>, <span class="pl-v">Zmax</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>.<span class="pl-en">min</span>(), <span class="pl-v">Z</span>.<span class="pl-en">max</span>()
<span class="pl-en">print</span>(<span class="pl-v">Zmin</span>, <span class="pl-v">Zmax</span>)</pre></div>
<h4><a id="user-content-14-create-a-random-vector-of-size-30-and-find-the-mean-value-" class="anchor" aria-hidden="true" href="#14-create-a-random-vector-of-size-30-and-find-the-mean-value-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>14. Create a random vector of size 30 and find the mean value (★☆☆)</h4>
<p><code>hint: mean</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>(<span class="pl-c1">30</span>)
<span class="pl-s1">m</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>.<span class="pl-en">mean</span>()
<span class="pl-en">print</span>(<span class="pl-s1">m</span>)</pre></div>
<h4><a id="user-content-15-create-a-2d-array-with-1-on-the-border-and-0-inside-" class="anchor" aria-hidden="true" href="#15-create-a-2d-array-with-1-on-the-border-and-0-inside-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>15. Create a 2d array with 1 on the border and 0 inside (★☆☆)</h4>
<p><code>hint: array[1:-1, 1:-1]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>] <span class="pl-c1">=</span> <span class="pl-c1">0</span>
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-16-how-to-add-a-border-filled-with-0s-around-an-existing-array-" class="anchor" aria-hidden="true" href="#16-how-to-add-a-border-filled-with-0s-around-an-existing-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>16. How to add a border (filled with 0's) around an existing array? (★☆☆)</h4>
<p><code>hint: np.pad</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">pad</span>(<span class="pl-v">Z</span>, <span class="pl-s1">pad_width</span><span class="pl-c1">=</span><span class="pl-c1">1</span>, <span class="pl-s1">mode</span><span class="pl-c1">=</span><span class="pl-s">'constant'</span>, <span class="pl-s1">constant_values</span><span class="pl-c1">=</span><span class="pl-c1">0</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-17-what-is-the-result-of-the-following-expression-" class="anchor" aria-hidden="true" href="#17-what-is-the-result-of-the-following-expression-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>17. What is the result of the following expression? (★☆☆)</h4>
<div class="highlight highlight-source-python"><pre><span class="pl-c1">0</span> <span class="pl-c1">*</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>
<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">==</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>
<span class="pl-s1">np</span>.<span class="pl-s1">inf</span> <span class="pl-c1">&gt;</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>
<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>
<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">in</span> <span class="pl-en">set</span>([<span class="pl-s1">np</span>.<span class="pl-s1">nan</span>])
<span class="pl-c1">0.3</span> <span class="pl-c1">==</span> <span class="pl-c1">3</span> <span class="pl-c1">*</span> <span class="pl-c1">0.1</span></pre></div>
<p><code>hint: NaN = not a number, inf = infinity</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-en">print</span>(<span class="pl-c1">0</span> <span class="pl-c1">*</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">==</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">inf</span> <span class="pl-c1">&gt;</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-s1">nan</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">nan</span> <span class="pl-c1">in</span> <span class="pl-en">set</span>([<span class="pl-s1">np</span>.<span class="pl-s1">nan</span>]))
<span class="pl-en">print</span>(<span class="pl-c1">0.3</span> <span class="pl-c1">==</span> <span class="pl-c1">3</span> <span class="pl-c1">*</span> <span class="pl-c1">0.1</span>)</pre></div>
<h4><a id="user-content-18-create-a-5x5-matrix-with-values-1234-just-below-the-diagonal-" class="anchor" aria-hidden="true" href="#18-create-a-5x5-matrix-with-values-1234-just-below-the-diagonal-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>18. Create a 5x5 matrix with values 1,2,3,4 just below the diagonal (★☆☆)</h4>
<p><code>hint: np.diag</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">diag</span>(<span class="pl-c1">1</span><span class="pl-c1">+</span><span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">4</span>),<span class="pl-s1">k</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-19-create-a-8x8-matrix-and-fill-it-with-a-checkerboard-pattern-" class="anchor" aria-hidden="true" href="#19-create-a-8x8-matrix-and-fill-it-with-a-checkerboard-pattern-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>19. Create a 8x8 matrix and fill it with a checkerboard pattern (★☆☆)</h4>
<p><code>hint: array[::2]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-c1">8</span>,<span class="pl-c1">8</span>),<span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">int</span>)
<span class="pl-v">Z</span>[<span class="pl-c1">1</span>::<span class="pl-c1">2</span>,::<span class="pl-c1">2</span>] <span class="pl-c1">=</span> <span class="pl-c1">1</span>
<span class="pl-v">Z</span>[::<span class="pl-c1">2</span>,<span class="pl-c1">1</span>::<span class="pl-c1">2</span>] <span class="pl-c1">=</span> <span class="pl-c1">1</span>
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-20-consider-a-678-shape-array-what-is-the-index-xyz-of-the-100th-element" class="anchor" aria-hidden="true" href="#20-consider-a-678-shape-array-what-is-the-index-xyz-of-the-100th-element"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>20. Consider a (6,7,8) shape array, what is the index (x,y,z) of the 100th element?</h4>
<p><code>hint: np.unravel_index</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">unravel_index</span>(<span class="pl-c1">99</span>,(<span class="pl-c1">6</span>,<span class="pl-c1">7</span>,<span class="pl-c1">8</span>)))</pre></div>
<h4><a id="user-content-21-create-a-checkerboard-8x8-matrix-using-the-tile-function-" class="anchor" aria-hidden="true" href="#21-create-a-checkerboard-8x8-matrix-using-the-tile-function-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>21. Create a checkerboard 8x8 matrix using the tile function (★☆☆)</h4>
<p><code>hint: np.tile</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">tile</span>( <span class="pl-s1">np</span>.<span class="pl-en">array</span>([[<span class="pl-c1">0</span>,<span class="pl-c1">1</span>],[<span class="pl-c1">1</span>,<span class="pl-c1">0</span>]]), (<span class="pl-c1">4</span>,<span class="pl-c1">4</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-22-normalize-a-5x5-random-matrix-" class="anchor" aria-hidden="true" href="#22-normalize-a-5x5-random-matrix-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>22. Normalize a 5x5 random matrix (★☆☆)</h4>
<p><code>hint: (x -mean)/std</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))
<span class="pl-v">Z</span> <span class="pl-c1">=</span> (<span class="pl-v">Z</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-en">mean</span> (<span class="pl-v">Z</span>)) <span class="pl-c1">/</span> (<span class="pl-s1">np</span>.<span class="pl-en">std</span> (<span class="pl-v">Z</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-23-create-a-custom-dtype-that-describes-a-color-as-four-unsigned-bytes-rgba-" class="anchor" aria-hidden="true" href="#23-create-a-custom-dtype-that-describes-a-color-as-four-unsigned-bytes-rgba-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>23. Create a custom dtype that describes a color as four unsigned bytes (RGBA) (★☆☆)</h4>
<p><code>hint: np.dtype</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">color</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">dtype</span>([(<span class="pl-s">"r"</span>, <span class="pl-s1">np</span>.<span class="pl-s1">ubyte</span>, <span class="pl-c1">1</span>),
                  (<span class="pl-s">"g"</span>, <span class="pl-s1">np</span>.<span class="pl-s1">ubyte</span>, <span class="pl-c1">1</span>),
                  (<span class="pl-s">"b"</span>, <span class="pl-s1">np</span>.<span class="pl-s1">ubyte</span>, <span class="pl-c1">1</span>),
                  (<span class="pl-s">"a"</span>, <span class="pl-s1">np</span>.<span class="pl-s1">ubyte</span>, <span class="pl-c1">1</span>)])</pre></div>
<h4><a id="user-content-24-multiply-a-5x3-matrix-by-a-3x2-matrix-real-matrix-product-" class="anchor" aria-hidden="true" href="#24-multiply-a-5x3-matrix-by-a-3x2-matrix-real-matrix-product-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>24. Multiply a 5x3 matrix by a 3x2 matrix (real matrix product) (★☆☆)</h4>
<p><code>hint:</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">dot</span>(<span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">5</span>,<span class="pl-c1">3</span>)), <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">3</span>,<span class="pl-c1">2</span>)))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)

<span class="pl-c"># Alternative solution, in Python 3.5 and above</span>
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">5</span>,<span class="pl-c1">3</span>)) @ <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">3</span>,<span class="pl-c1">2</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-25-given-a-1d-array-negate-all-elements-which-are-between-3-and-8-in-place-" class="anchor" aria-hidden="true" href="#25-given-a-1d-array-negate-all-elements-which-are-between-3-and-8-in-place-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>25. Given a 1D array, negate all elements which are between 3 and 8, in place. (★☆☆)</h4>
<p><code>hint: &gt;, &lt;</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Evgeni Burovski</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">11</span>)
<span class="pl-v">Z</span>[(<span class="pl-c1">3</span> <span class="pl-c1">&lt;</span> <span class="pl-v">Z</span>) <span class="pl-c1">&amp;</span> (<span class="pl-v">Z</span> <span class="pl-c1">&lt;=</span> <span class="pl-c1">8</span>)] <span class="pl-c1">*=</span> <span class="pl-c1">-</span><span class="pl-c1">1</span>
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-26-what-is-the-output-of-the-following-script-" class="anchor" aria-hidden="true" href="#26-what-is-the-output-of-the-following-script-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>26. What is the output of the following script? (★☆☆)</h4>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jake VanderPlas</span>

<span class="pl-en">print</span>(<span class="pl-en">sum</span>(<span class="pl-en">range</span>(<span class="pl-c1">5</span>),<span class="pl-c1">-</span><span class="pl-c1">1</span>))
<span class="pl-k">from</span> <span class="pl-s1">numpy</span> <span class="pl-k">import</span> <span class="pl-c1">*</span>
<span class="pl-en">print</span>(<span class="pl-en">sum</span>(<span class="pl-en">range</span>(<span class="pl-c1">5</span>),<span class="pl-c1">-</span><span class="pl-c1">1</span>))</pre></div>
<p><code>hint: np.sum</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jake VanderPlas</span>

<span class="pl-en">print</span>(<span class="pl-en">sum</span>(<span class="pl-en">range</span>(<span class="pl-c1">5</span>),<span class="pl-c1">-</span><span class="pl-c1">1</span>))
<span class="pl-k">from</span> <span class="pl-s1">numpy</span> <span class="pl-k">import</span> <span class="pl-c1">*</span>
<span class="pl-en">print</span>(<span class="pl-en">sum</span>(<span class="pl-en">range</span>(<span class="pl-c1">5</span>),<span class="pl-c1">-</span><span class="pl-c1">1</span>))</pre></div>
<h4><a id="user-content-27-consider-an-integer-vector-z-which-of-these-expressions-are-legal-" class="anchor" aria-hidden="true" href="#27-consider-an-integer-vector-z-which-of-these-expressions-are-legal-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>27. Consider an integer vector Z, which of these expressions are legal? (★☆☆)</h4>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span><span class="pl-c1">**</span><span class="pl-v">Z</span>
<span class="pl-c1">2</span> <span class="pl-c1">&lt;&lt;</span> <span class="pl-v">Z</span> <span class="pl-c1">&gt;&gt;</span> <span class="pl-c1">2</span>
<span class="pl-v">Z</span> <span class="pl-c1">&lt;</span><span class="pl-c1">-</span> <span class="pl-v">Z</span>
<span class="pl-c1">1j</span><span class="pl-c1">*</span><span class="pl-v">Z</span>
<span class="pl-v">Z</span><span class="pl-c1">/</span><span class="pl-c1">1</span><span class="pl-c1">/</span><span class="pl-c1">1</span>
<span class="pl-v">Z</span><span class="pl-c1">&lt;</span><span class="pl-v">Z</span><span class="pl-c1">&gt;</span><span class="pl-v">Z</span></pre></div>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span><span class="pl-c1">**</span><span class="pl-v">Z</span>
<span class="pl-c1">2</span> <span class="pl-c1">&lt;&lt;</span> <span class="pl-v">Z</span> <span class="pl-c1">&gt;&gt;</span> <span class="pl-c1">2</span>
<span class="pl-v">Z</span> <span class="pl-c1">&lt;</span><span class="pl-c1">-</span> <span class="pl-v">Z</span>
<span class="pl-c1">1j</span><span class="pl-c1">*</span><span class="pl-v">Z</span>
<span class="pl-v">Z</span><span class="pl-c1">/</span><span class="pl-c1">1</span><span class="pl-c1">/</span><span class="pl-c1">1</span>
<span class="pl-v">Z</span><span class="pl-c1">&lt;</span><span class="pl-v">Z</span><span class="pl-c1">&gt;</span><span class="pl-v">Z</span></pre></div>
<h4><a id="user-content-28-what-are-the-result-of-the-following-expressions" class="anchor" aria-hidden="true" href="#28-what-are-the-result-of-the-following-expressions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>28. What are the result of the following expressions?</h4>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>) <span class="pl-c1">/</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>)
<span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>) <span class="pl-c1">//</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>)
<span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-s1">np</span>.<span class="pl-s1">nan</span>]).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>).<span class="pl-en">astype</span>(<span class="pl-s1">float</span>)</pre></div>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>) <span class="pl-c1">/</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>))
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>) <span class="pl-c1">//</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-c1">0</span>))
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-s1">np</span>.<span class="pl-s1">nan</span>]).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>).<span class="pl-en">astype</span>(<span class="pl-s1">float</span>))</pre></div>
<h4><a id="user-content-29-how-to-round-away-from-zero-a-float-array--" class="anchor" aria-hidden="true" href="#29-how-to-round-away-from-zero-a-float-array--"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>29. How to round away from zero a float array ? (★☆☆)</h4>
<p><code>hint: np.uniform, np.copysign, np.ceil, np.abs</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Charles R Harris</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>,<span class="pl-c1">+</span><span class="pl-c1">10</span>,<span class="pl-c1">10</span>)
<span class="pl-en">print</span> (<span class="pl-s1">np</span>.<span class="pl-en">copysign</span>(<span class="pl-s1">np</span>.<span class="pl-en">ceil</span>(<span class="pl-s1">np</span>.<span class="pl-en">abs</span>(<span class="pl-v">Z</span>)), <span class="pl-v">Z</span>))</pre></div>
<h4><a id="user-content-30-how-to-find-common-values-between-two-arrays-" class="anchor" aria-hidden="true" href="#30-how-to-find-common-values-between-two-arrays-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>30. How to find common values between two arrays? (★☆☆)</h4>
<p><code>hint: np.intersect1d</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z1</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,<span class="pl-c1">10</span>)
<span class="pl-v">Z2</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,<span class="pl-c1">10</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">intersect1d</span>(<span class="pl-v">Z1</span>,<span class="pl-v">Z2</span>))</pre></div>
<h4><a id="user-content-31-how-to-ignore-all-numpy-warnings-not-recommended-" class="anchor" aria-hidden="true" href="#31-how-to-ignore-all-numpy-warnings-not-recommended-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>31. How to ignore all numpy warnings (not recommended)? (★☆☆)</h4>
<p><code>hint: np.seterr, np.errstate</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Suicide mode on</span>
<span class="pl-s1">defaults</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">seterr</span>(<span class="pl-s1">all</span><span class="pl-c1">=</span><span class="pl-s">"ignore"</span>)
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-c1">1</span>) <span class="pl-c1">/</span> <span class="pl-c1">0</span>

<span class="pl-c"># Back to sanity</span>
<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">seterr</span>(<span class="pl-c1">**</span><span class="pl-s1">defaults</span>)

<span class="pl-c"># Equivalently with a context manager</span>
<span class="pl-s1">nz</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">nonzero</span>([<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">0</span>,<span class="pl-c1">0</span>,<span class="pl-c1">4</span>,<span class="pl-c1">0</span>])
<span class="pl-en">print</span>(<span class="pl-s1">nz</span>)</pre></div>
<h4><a id="user-content-32-is-the-following-expressions-true-" class="anchor" aria-hidden="true" href="#32-is-the-following-expressions-true-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>32. Is the following expressions true? (★☆☆)</h4>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>) <span class="pl-c1">==</span> <span class="pl-s1">np</span>.<span class="pl-s1">emath</span>.<span class="pl-en">sqrt</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>)</pre></div>
<p><code>hint: imaginary number</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>) <span class="pl-c1">==</span> <span class="pl-s1">np</span>.<span class="pl-s1">emath</span>.<span class="pl-en">sqrt</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>)</pre></div>
<h4><a id="user-content-33-how-to-get-the-dates-of-yesterday-today-and-tomorrow-" class="anchor" aria-hidden="true" href="#33-how-to-get-the-dates-of-yesterday-today-and-tomorrow-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>33. How to get the dates of yesterday, today and tomorrow? (★☆☆)</h4>
<p><code>hint: np.datetime64, np.timedelta64</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">yesterday</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">datetime64</span>(<span class="pl-s">'today'</span>, <span class="pl-s">'D'</span>) <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-en">timedelta64</span>(<span class="pl-c1">1</span>, <span class="pl-s">'D'</span>)
<span class="pl-s1">today</span>     <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">datetime64</span>(<span class="pl-s">'today'</span>, <span class="pl-s">'D'</span>)
<span class="pl-s1">tomorrow</span>  <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">datetime64</span>(<span class="pl-s">'today'</span>, <span class="pl-s">'D'</span>) <span class="pl-c1">+</span> <span class="pl-s1">np</span>.<span class="pl-en">timedelta64</span>(<span class="pl-c1">1</span>, <span class="pl-s">'D'</span>)</pre></div>
<h4><a id="user-content-34-how-to-get-all-the-dates-corresponding-to-the-month-of-july-2016-" class="anchor" aria-hidden="true" href="#34-how-to-get-all-the-dates-corresponding-to-the-month-of-july-2016-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>34. How to get all the dates corresponding to the month of July 2016? (★★☆)</h4>
<p><code>hint: np.arange(dtype=datetime64['D'])</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-s">'2016-07'</span>, <span class="pl-s">'2016-08'</span>, <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s">'datetime64[D]'</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-35-how-to-compute-ab-a2-in-place-without-copy-" class="anchor" aria-hidden="true" href="#35-how-to-compute-ab-a2-in-place-without-copy-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>35. How to compute ((A+B)*(-A/2)) in place (without copy)? (★★☆)</h4>
<p><code>hint: np.add(out=), np.negative(out=), np.multiply(out=), np.divide(out=)</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-c1">3</span>)<span class="pl-c1">*</span><span class="pl-c1">1</span>
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-c1">3</span>)<span class="pl-c1">*</span><span class="pl-c1">2</span>
<span class="pl-v">C</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-c1">3</span>)<span class="pl-c1">*</span><span class="pl-c1">3</span>
<span class="pl-s1">np</span>.<span class="pl-en">add</span>(<span class="pl-v">A</span>,<span class="pl-v">B</span>,<span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">B</span>)
<span class="pl-s1">np</span>.<span class="pl-en">divide</span>(<span class="pl-v">A</span>,<span class="pl-c1">2</span>,<span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">A</span>)
<span class="pl-s1">np</span>.<span class="pl-en">negative</span>(<span class="pl-v">A</span>,<span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">A</span>)
<span class="pl-s1">np</span>.<span class="pl-en">multiply</span>(<span class="pl-v">A</span>,<span class="pl-v">B</span>,<span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">A</span>)</pre></div>
<h4><a id="user-content-36-extract-the-integer-part-of-a-random-array-using-5-different-methods-" class="anchor" aria-hidden="true" href="#36-extract-the-integer-part-of-a-random-array-using-5-different-methods-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>36. Extract the integer part of a random array using 5 different methods (★★☆)</h4>
<p><code>hint: %, np.floor, np.ceil, astype, np.trunc</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,<span class="pl-c1">10</span>)

<span class="pl-en">print</span> (<span class="pl-v">Z</span> <span class="pl-c1">-</span> <span class="pl-v">Z</span><span class="pl-c1">%</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span> (<span class="pl-s1">np</span>.<span class="pl-en">floor</span>(<span class="pl-v">Z</span>))
<span class="pl-en">print</span> (<span class="pl-s1">np</span>.<span class="pl-en">ceil</span>(<span class="pl-v">Z</span>)<span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span> (<span class="pl-v">Z</span>.<span class="pl-en">astype</span>(<span class="pl-s1">int</span>))
<span class="pl-en">print</span> (<span class="pl-s1">np</span>.<span class="pl-en">trunc</span>(<span class="pl-v">Z</span>))</pre></div>
<h4><a id="user-content-37-create-a-5x5-matrix-with-row-values-ranging-from-0-to-4-" class="anchor" aria-hidden="true" href="#37-create-a-5x5-matrix-with-row-values-ranging-from-0-to-4-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>37. Create a 5x5 matrix with row values ranging from 0 to 4 (★★☆)</h4>
<p><code>hint: np.arange</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))
<span class="pl-v">Z</span> <span class="pl-c1">+=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">5</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-38-consider-a-generator-function-that-generates-10-integers-and-use-it-to-build-an-array-" class="anchor" aria-hidden="true" href="#38-consider-a-generator-function-that-generates-10-integers-and-use-it-to-build-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>38. Consider a generator function that generates 10 integers and use it to build an array (★☆☆)</h4>
<p><code>hint: np.fromiter</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">def</span> <span class="pl-en">generate</span>():
    <span class="pl-k">for</span> <span class="pl-s1">x</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">10</span>):
        <span class="pl-k">yield</span> <span class="pl-s1">x</span>
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">fromiter</span>(<span class="pl-en">generate</span>(),<span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">float</span>,<span class="pl-s1">count</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-39-create-a-vector-of-size-10-with-values-ranging-from-0-to-1-both-excluded-" class="anchor" aria-hidden="true" href="#39-create-a-vector-of-size-10-with-values-ranging-from-0-to-1-both-excluded-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>39. Create a vector of size 10 with values ranging from 0 to 1, both excluded (★★☆)</h4>
<p><code>hint: np.linspace</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">11</span>,<span class="pl-s1">endpoint</span><span class="pl-c1">=</span><span class="pl-c1">False</span>)[<span class="pl-c1">1</span>:]
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-40-create-a-random-vector-of-size-10-and-sort-it-" class="anchor" aria-hidden="true" href="#40-create-a-random-vector-of-size-10-and-sort-it-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>40. Create a random vector of size 10 and sort it (★★☆)</h4>
<p><code>hint: sort</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>(<span class="pl-c1">10</span>)
<span class="pl-v">Z</span>.<span class="pl-en">sort</span>()
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-41-how-to-sum-a-small-array-faster-than-npsum-" class="anchor" aria-hidden="true" href="#41-how-to-sum-a-small-array-faster-than-npsum-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>41. How to sum a small array faster than np.sum? (★★☆)</h4>
<p><code>hint: np.add.reduce</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Evgeni Burovski</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">10</span>)
<span class="pl-s1">np</span>.<span class="pl-s1">add</span>.<span class="pl-en">reduce</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-42-consider-two-random-array-a-and-b-check-if-they-are-equal-" class="anchor" aria-hidden="true" href="#42-consider-two-random-array-a-and-b-check-if-they-are-equal-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>42. Consider two random array A and B, check if they are equal (★★☆)</h4>
<p><code>hint: np.allclose, np.array_equal</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,<span class="pl-c1">5</span>)
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,<span class="pl-c1">5</span>)

<span class="pl-c"># Assuming identical shape of the arrays and a tolerance for the comparison of values</span>
<span class="pl-s1">equal</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">allclose</span>(<span class="pl-v">A</span>,<span class="pl-v">B</span>)
<span class="pl-en">print</span>(<span class="pl-s1">equal</span>)

<span class="pl-c"># Checking both the shape and the element values, no tolerance (values have to be exactly equal)</span>
<span class="pl-s1">equal</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array_equal</span>(<span class="pl-v">A</span>,<span class="pl-v">B</span>)
<span class="pl-en">print</span>(<span class="pl-s1">equal</span>)</pre></div>
<h4><a id="user-content-43-make-an-array-immutable-read-only-" class="anchor" aria-hidden="true" href="#43-make-an-array-immutable-read-only-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>43. Make an array immutable (read-only) (★★☆)</h4>
<p><code>hint: flags.writeable</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>(<span class="pl-c1">10</span>)
<span class="pl-v">Z</span>.<span class="pl-s1">flags</span>.<span class="pl-s1">writeable</span> <span class="pl-c1">=</span> <span class="pl-c1">False</span>
<span class="pl-v">Z</span>[<span class="pl-c1">0</span>] <span class="pl-c1">=</span> <span class="pl-c1">1</span></pre></div>
<h4><a id="user-content-44-consider-a-random-10x2-matrix-representing-cartesian-coordinates-convert-them-to-polar-coordinates-" class="anchor" aria-hidden="true" href="#44-consider-a-random-10x2-matrix-representing-cartesian-coordinates-convert-them-to-polar-coordinates-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>44. Consider a random 10x2 matrix representing cartesian coordinates, convert them to polar coordinates (★★☆)</h4>
<p><code>hint: np.sqrt, np.arctan2</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-v">X</span>,<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>[:,<span class="pl-c1">0</span>], <span class="pl-v">Z</span>[:,<span class="pl-c1">1</span>]
<span class="pl-v">R</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>(<span class="pl-v">X</span><span class="pl-c1">**</span><span class="pl-c1">2</span><span class="pl-c1">+</span><span class="pl-v">Y</span><span class="pl-c1">**</span><span class="pl-c1">2</span>)
<span class="pl-v">T</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arctan2</span>(<span class="pl-v">Y</span>,<span class="pl-v">X</span>)
<span class="pl-en">print</span>(<span class="pl-v">R</span>)
<span class="pl-en">print</span>(<span class="pl-v">T</span>)</pre></div>
<h4><a id="user-content-45-create-random-vector-of-size-10-and-replace-the-maximum-value-by-0-" class="anchor" aria-hidden="true" href="#45-create-random-vector-of-size-10-and-replace-the-maximum-value-by-0-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>45. Create random vector of size 10 and replace the maximum value by 0 (★★☆)</h4>
<p><code>hint: argmax</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>(<span class="pl-c1">10</span>)
<span class="pl-v">Z</span>[<span class="pl-v">Z</span>.<span class="pl-en">argmax</span>()] <span class="pl-c1">=</span> <span class="pl-c1">0</span>
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-46-create-a-structured-array-with-x-and-y-coordinates-covering-the-01x01-area-" class="anchor" aria-hidden="true" href="#46-create-a-structured-array-with-x-and-y-coordinates-covering-the-01x01-area-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>46. Create a structured array with <code>x</code> and <code>y</code> coordinates covering the [0,1]x[0,1] area (★★☆)</h4>
<p><code>hint: np.meshgrid</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>), [(<span class="pl-s">'x'</span>,<span class="pl-s1">float</span>),(<span class="pl-s">'y'</span>,<span class="pl-s1">float</span>)])
<span class="pl-v">Z</span>[<span class="pl-s">'x'</span>], <span class="pl-v">Z</span>[<span class="pl-s">'y'</span>] <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">meshgrid</span>(<span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">5</span>),
                             <span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">5</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-47-given-two-arrays-x-and-y-construct-the-cauchy-matrix-c-cij-1xi---yj" class="anchor" aria-hidden="true" href="#47-given-two-arrays-x-and-y-construct-the-cauchy-matrix-c-cij-1xi---yj"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>47. Given two arrays, X and Y, construct the Cauchy matrix C (Cij =1/(xi - yj))</h4>
<p><code>hint: np.subtract.outer</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Evgeni Burovski</span>

<span class="pl-v">X</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">8</span>)
<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-v">X</span> <span class="pl-c1">+</span> <span class="pl-c1">0.5</span>
<span class="pl-v">C</span> <span class="pl-c1">=</span> <span class="pl-c1">1.0</span> <span class="pl-c1">/</span> <span class="pl-s1">np</span>.<span class="pl-s1">subtract</span>.<span class="pl-en">outer</span>(<span class="pl-v">X</span>, <span class="pl-v">Y</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-s1">linalg</span>.<span class="pl-en">det</span>(<span class="pl-v">C</span>))</pre></div>
<h4><a id="user-content-48-print-the-minimum-and-maximum-representable-value-for-each-numpy-scalar-type-" class="anchor" aria-hidden="true" href="#48-print-the-minimum-and-maximum-representable-value-for-each-numpy-scalar-type-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>48. Print the minimum and maximum representable value for each numpy scalar type (★★☆)</h4>
<p><code>hint: np.iinfo, np.finfo, eps</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">for</span> <span class="pl-s1">dtype</span> <span class="pl-c1">in</span> [<span class="pl-s1">np</span>.<span class="pl-s1">int8</span>, <span class="pl-s1">np</span>.<span class="pl-s1">int32</span>, <span class="pl-s1">np</span>.<span class="pl-s1">int64</span>]:
   <span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">iinfo</span>(<span class="pl-s1">dtype</span>).<span class="pl-s1">min</span>)
   <span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">iinfo</span>(<span class="pl-s1">dtype</span>).<span class="pl-s1">max</span>)
<span class="pl-k">for</span> <span class="pl-s1">dtype</span> <span class="pl-c1">in</span> [<span class="pl-s1">np</span>.<span class="pl-s1">float32</span>, <span class="pl-s1">np</span>.<span class="pl-s1">float64</span>]:
   <span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">finfo</span>(<span class="pl-s1">dtype</span>).<span class="pl-s1">min</span>)
   <span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">finfo</span>(<span class="pl-s1">dtype</span>).<span class="pl-s1">max</span>)
   <span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">finfo</span>(<span class="pl-s1">dtype</span>).<span class="pl-s1">eps</span>)</pre></div>
<h4><a id="user-content-49-how-to-print-all-the-values-of-an-array-" class="anchor" aria-hidden="true" href="#49-how-to-print-all-the-values-of-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>49. How to print all the values of an array? (★★☆)</h4>
<p><code>hint: np.set_printoptions</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-s1">np</span>.<span class="pl-en">set_printoptions</span>(<span class="pl-s1">threshold</span><span class="pl-c1">=</span><span class="pl-s1">np</span>.<span class="pl-s1">nan</span>)
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-c1">16</span>,<span class="pl-c1">16</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-50-how-to-find-the-closest-value-to-a-given-scalar-in-a-vector-" class="anchor" aria-hidden="true" href="#50-how-to-find-the-closest-value-to-a-given-scalar-in-a-vector-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>50. How to find the closest value (to a given scalar) in a vector? (★★☆)</h4>
<p><code>hint: argmin</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">100</span>)
<span class="pl-s1">v</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">100</span>)
<span class="pl-s1">index</span> <span class="pl-c1">=</span> (<span class="pl-s1">np</span>.<span class="pl-en">abs</span>(<span class="pl-v">Z</span><span class="pl-c1">-</span><span class="pl-s1">v</span>)).<span class="pl-en">argmin</span>()
<span class="pl-en">print</span>(<span class="pl-v">Z</span>[<span class="pl-s1">index</span>])</pre></div>
<h4><a id="user-content-51-create-a-structured-array-representing-a-position-xy-and-a-color-rgb-" class="anchor" aria-hidden="true" href="#51-create-a-structured-array-representing-a-position-xy-and-a-color-rgb-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>51. Create a structured array representing a position (x,y) and a color (r,g,b) (★★☆)</h4>
<p><code>hint: dtype</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>(<span class="pl-c1">10</span>, [ (<span class="pl-s">'position'</span>, [ (<span class="pl-s">'x'</span>, <span class="pl-s1">float</span>, <span class="pl-c1">1</span>),
                                  (<span class="pl-s">'y'</span>, <span class="pl-s1">float</span>, <span class="pl-c1">1</span>)]),
                   (<span class="pl-s">'color'</span>,    [ (<span class="pl-s">'r'</span>, <span class="pl-s1">float</span>, <span class="pl-c1">1</span>),
                                  (<span class="pl-s">'g'</span>, <span class="pl-s1">float</span>, <span class="pl-c1">1</span>),
                                  (<span class="pl-s">'b'</span>, <span class="pl-s1">float</span>, <span class="pl-c1">1</span>)])])
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-52-consider-a-random-vector-with-shape-1002-representing-coordinates-find-point-by-point-distances-" class="anchor" aria-hidden="true" href="#52-consider-a-random-vector-with-shape-1002-representing-coordinates-find-point-by-point-distances-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>52. Consider a random vector with shape (100,2) representing coordinates, find point by point distances (★★☆)</h4>
<p><code>hint: np.atleast_2d, T, np.sqrt</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-v">X</span>,<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">atleast_2d</span>(<span class="pl-v">Z</span>[:,<span class="pl-c1">0</span>], <span class="pl-v">Z</span>[:,<span class="pl-c1">1</span>])
<span class="pl-v">D</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>( (<span class="pl-v">X</span><span class="pl-c1">-</span><span class="pl-v">X</span>.<span class="pl-v">T</span>)<span class="pl-c1">**</span><span class="pl-c1">2</span> <span class="pl-c1">+</span> (<span class="pl-v">Y</span><span class="pl-c1">-</span><span class="pl-v">Y</span>.<span class="pl-v">T</span>)<span class="pl-c1">**</span><span class="pl-c1">2</span>)
<span class="pl-en">print</span>(<span class="pl-v">D</span>)

<span class="pl-c"># Much faster with scipy</span>
<span class="pl-k">import</span> <span class="pl-s1">scipy</span>
<span class="pl-c"># Thanks Gavin Heverly-Coulson (#issue 1)</span>
<span class="pl-k">import</span> <span class="pl-s1">scipy</span>.<span class="pl-s1">spatial</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">random</span>((<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-v">D</span> <span class="pl-c1">=</span> <span class="pl-s1">scipy</span>.<span class="pl-s1">spatial</span>.<span class="pl-s1">distance</span>.<span class="pl-en">cdist</span>(<span class="pl-v">Z</span>,<span class="pl-v">Z</span>)
<span class="pl-en">print</span>(<span class="pl-v">D</span>)</pre></div>
<h4><a id="user-content-53-how-to-convert-a-float-32-bits-array-into-an-integer-32-bits-in-place" class="anchor" aria-hidden="true" href="#53-how-to-convert-a-float-32-bits-array-into-an-integer-32-bits-in-place"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>53. How to convert a float (32 bits) array into an integer (32 bits) in place?</h4>
<p><code>hint: view and [:] =</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Thanks Vikas (https://stackoverflow.com/a/10622758/5989906)</span>
<span class="pl-c"># &amp; unutbu (https://stackoverflow.com/a/4396247/5989906)</span>
<span class="pl-v">Z</span> <span class="pl-c1">=</span> (<span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">rand</span>(<span class="pl-c1">10</span>)<span class="pl-c1">*</span><span class="pl-c1">100</span>).<span class="pl-en">astype</span>(<span class="pl-s1">np</span>.<span class="pl-s1">float32</span>)
<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>.<span class="pl-en">view</span>(<span class="pl-s1">np</span>.<span class="pl-s1">int32</span>)
<span class="pl-v">Y</span>[:] <span class="pl-c1">=</span> <span class="pl-v">Z</span>
<span class="pl-en">print</span>(<span class="pl-v">Y</span>)</pre></div>
<h4><a id="user-content-54-how-to-read-the-following-file-" class="anchor" aria-hidden="true" href="#54-how-to-read-the-following-file-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>54. How to read the following file? (★★☆)</h4>
<pre><code>1, 2, 3, 4, 5
6,  ,  , 7, 8
 ,  , 9,10,11
</code></pre>
<p><code>hint: np.genfromtxt</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">from</span> <span class="pl-s1">io</span> <span class="pl-k">import</span> <span class="pl-v">StringIO</span>

<span class="pl-c"># Fake file</span>
<span class="pl-s1">s</span> <span class="pl-c1">=</span> <span class="pl-v">StringIO</span>(<span class="pl-s">'''1, 2, 3, 4, 5</span>
<span class="pl-s"></span>
<span class="pl-s">                6,  ,  , 7, 8</span>
<span class="pl-s"></span>
<span class="pl-s">                 ,  , 9,10,11</span>
<span class="pl-s">'''</span>)
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">genfromtxt</span>(<span class="pl-s1">s</span>, <span class="pl-s1">delimiter</span><span class="pl-c1">=</span><span class="pl-s">","</span>, <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">np</span>.<span class="pl-s1">int</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-55-what-is-the-equivalent-of-enumerate-for-numpy-arrays-" class="anchor" aria-hidden="true" href="#55-what-is-the-equivalent-of-enumerate-for-numpy-arrays-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>55. What is the equivalent of enumerate for numpy arrays? (★★☆)</h4>
<p><code>hint: np.ndenumerate, np.ndindex</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">9</span>).<span class="pl-en">reshape</span>(<span class="pl-c1">3</span>,<span class="pl-c1">3</span>)
<span class="pl-k">for</span> <span class="pl-s1">index</span>, <span class="pl-s1">value</span> <span class="pl-c1">in</span> <span class="pl-s1">np</span>.<span class="pl-en">ndenumerate</span>(<span class="pl-v">Z</span>):
    <span class="pl-en">print</span>(<span class="pl-s1">index</span>, <span class="pl-s1">value</span>)
<span class="pl-k">for</span> <span class="pl-s1">index</span> <span class="pl-c1">in</span> <span class="pl-s1">np</span>.<span class="pl-en">ndindex</span>(<span class="pl-v">Z</span>.<span class="pl-s1">shape</span>):
    <span class="pl-en">print</span>(<span class="pl-s1">index</span>, <span class="pl-v">Z</span>[<span class="pl-s1">index</span>])</pre></div>
<h4><a id="user-content-56-generate-a-generic-2d-gaussian-like-array-" class="anchor" aria-hidden="true" href="#56-generate-a-generic-2d-gaussian-like-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>56. Generate a generic 2D Gaussian-like array (★★☆)</h4>
<p><code>hint: np.meshgrid, np.exp</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">X</span>, <span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">meshgrid</span>(<span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>,<span class="pl-c1">10</span>), <span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>,<span class="pl-c1">10</span>))
<span class="pl-v">D</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>(<span class="pl-v">X</span><span class="pl-c1">*</span><span class="pl-v">X</span><span class="pl-c1">+</span><span class="pl-v">Y</span><span class="pl-c1">*</span><span class="pl-v">Y</span>)
<span class="pl-s1">sigma</span>, <span class="pl-s1">mu</span> <span class="pl-c1">=</span> <span class="pl-c1">1.0</span>, <span class="pl-c1">0.0</span>
<span class="pl-v">G</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">exp</span>(<span class="pl-c1">-</span>( (<span class="pl-v">D</span><span class="pl-c1">-</span><span class="pl-s1">mu</span>)<span class="pl-c1">**</span><span class="pl-c1">2</span> <span class="pl-c1">/</span> ( <span class="pl-c1">2.0</span> <span class="pl-c1">*</span> <span class="pl-s1">sigma</span><span class="pl-c1">**</span><span class="pl-c1">2</span> ) ) )
<span class="pl-en">print</span>(<span class="pl-v">G</span>)</pre></div>
<h4><a id="user-content-57-how-to-randomly-place-p-elements-in-a-2d-array-" class="anchor" aria-hidden="true" href="#57-how-to-randomly-place-p-elements-in-a-2d-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>57. How to randomly place p elements in a 2D array? (★★☆)</h4>
<p><code>hint: np.put, np.random.choice</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Divakar</span>

<span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">10</span>
<span class="pl-s1">p</span> <span class="pl-c1">=</span> <span class="pl-c1">3</span>
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-s1">n</span>,<span class="pl-s1">n</span>))
<span class="pl-s1">np</span>.<span class="pl-en">put</span>(<span class="pl-v">Z</span>, <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">choice</span>(<span class="pl-en">range</span>(<span class="pl-s1">n</span><span class="pl-c1">*</span><span class="pl-s1">n</span>), <span class="pl-s1">p</span>, <span class="pl-s1">replace</span><span class="pl-c1">=</span><span class="pl-c1">False</span>),<span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-58-subtract-the-mean-of-each-row-of-a-matrix-" class="anchor" aria-hidden="true" href="#58-subtract-the-mean-of-each-row-of-a-matrix-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>58. Subtract the mean of each row of a matrix (★★☆)</h4>
<p><code>hint: mean(axis=,keepdims=)</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Warren Weckesser</span>

<span class="pl-v">X</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">rand</span>(<span class="pl-c1">5</span>, <span class="pl-c1">10</span>)

<span class="pl-c"># Recent versions of numpy</span>
<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-v">X</span> <span class="pl-c1">-</span> <span class="pl-v">X</span>.<span class="pl-en">mean</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>, <span class="pl-s1">keepdims</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)

<span class="pl-c"># Older versions of numpy</span>
<span class="pl-v">Y</span> <span class="pl-c1">=</span> <span class="pl-v">X</span> <span class="pl-c1">-</span> <span class="pl-v">X</span>.<span class="pl-en">mean</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>).<span class="pl-en">reshape</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>, <span class="pl-c1">1</span>)

<span class="pl-en">print</span>(<span class="pl-v">Y</span>)</pre></div>
<h4><a id="user-content-59-how-to-sort-an-array-by-the-nth-column-" class="anchor" aria-hidden="true" href="#59-how-to-sort-an-array-by-the-nth-column-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>59. How to sort an array by the nth column? (★★☆)</h4>
<p><code>hint: argsort</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Steve Tjoa</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">3</span>,<span class="pl-c1">3</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>[<span class="pl-v">Z</span>[:,<span class="pl-c1">1</span>].<span class="pl-en">argsort</span>()])</pre></div>
<h4><a id="user-content-60-how-to-tell-if-a-given-2d-array-has-null-columns-" class="anchor" aria-hidden="true" href="#60-how-to-tell-if-a-given-2d-array-has-null-columns-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>60. How to tell if a given 2D array has null columns? (★★☆)</h4>
<p><code>hint: any, ~</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Warren Weckesser</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">3</span>,(<span class="pl-c1">3</span>,<span class="pl-c1">10</span>))
<span class="pl-en">print</span>((<span class="pl-c1">~</span><span class="pl-v">Z</span>.<span class="pl-en">any</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">0</span>)).<span class="pl-en">any</span>())</pre></div>
<h4><a id="user-content-61-find-the-nearest-value-from-a-given-value-in-an-array-" class="anchor" aria-hidden="true" href="#61-find-the-nearest-value-from-a-given-value-in-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>61. Find the nearest value from a given value in an array (★★☆)</h4>
<p><code>hint: np.abs, argmin, flat</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">10</span>)
<span class="pl-s1">z</span> <span class="pl-c1">=</span> <span class="pl-c1">0.5</span>
<span class="pl-s1">m</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>.<span class="pl-s1">flat</span>[<span class="pl-s1">np</span>.<span class="pl-en">abs</span>(<span class="pl-v">Z</span> <span class="pl-c1">-</span> <span class="pl-s1">z</span>).<span class="pl-en">argmin</span>()]
<span class="pl-en">print</span>(<span class="pl-s1">m</span>)</pre></div>
<h4><a id="user-content-62-considering-two-arrays-with-shape-13-and-31-how-to-compute-their-sum-using-an-iterator-" class="anchor" aria-hidden="true" href="#62-considering-two-arrays-with-shape-13-and-31-how-to-compute-their-sum-using-an-iterator-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>62. Considering two arrays with shape (1,3) and (3,1), how to compute their sum using an iterator? (★★☆)</h4>
<p><code>hint: np.nditer</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">3</span>).<span class="pl-en">reshape</span>(<span class="pl-c1">3</span>,<span class="pl-c1">1</span>)
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">3</span>).<span class="pl-en">reshape</span>(<span class="pl-c1">1</span>,<span class="pl-c1">3</span>)
<span class="pl-s1">it</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">nditer</span>([<span class="pl-v">A</span>,<span class="pl-v">B</span>,<span class="pl-c1">None</span>])
<span class="pl-k">for</span> <span class="pl-s1">x</span>,<span class="pl-s1">y</span>,<span class="pl-s1">z</span> <span class="pl-c1">in</span> <span class="pl-s1">it</span>: <span class="pl-s1">z</span>[...] <span class="pl-c1">=</span> <span class="pl-s1">x</span> <span class="pl-c1">+</span> <span class="pl-s1">y</span>
<span class="pl-en">print</span>(<span class="pl-s1">it</span>.<span class="pl-s1">operands</span>[<span class="pl-c1">2</span>])</pre></div>
<h4><a id="user-content-63-create-an-array-class-that-has-a-name-attribute-" class="anchor" aria-hidden="true" href="#63-create-an-array-class-that-has-a-name-attribute-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>63. Create an array class that has a name attribute (★★☆)</h4>
<p><code>hint: class method</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">class</span> <span class="pl-v">NamedArray</span>(<span class="pl-s1">np</span>.<span class="pl-s1">ndarray</span>):
    <span class="pl-k">def</span> <span class="pl-en">__new__</span>(<span class="pl-s1">cls</span>, <span class="pl-s1">array</span>, <span class="pl-s1">name</span><span class="pl-c1">=</span><span class="pl-s">"no name"</span>):
        <span class="pl-s1">obj</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">asarray</span>(<span class="pl-s1">array</span>).<span class="pl-en">view</span>(<span class="pl-s1">cls</span>)
        <span class="pl-s1">obj</span>.<span class="pl-s1">name</span> <span class="pl-c1">=</span> <span class="pl-s1">name</span>
        <span class="pl-k">return</span> <span class="pl-s1">obj</span>
    <span class="pl-k">def</span> <span class="pl-en">__array_finalize__</span>(<span class="pl-s1">self</span>, <span class="pl-s1">obj</span>):
        <span class="pl-k">if</span> <span class="pl-s1">obj</span> <span class="pl-c1">is</span> <span class="pl-c1">None</span>: <span class="pl-k">return</span>
        <span class="pl-s1">self</span>.<span class="pl-s1">info</span> <span class="pl-c1">=</span> <span class="pl-en">getattr</span>(<span class="pl-s1">obj</span>, <span class="pl-s">'name'</span>, <span class="pl-s">"no name"</span>)

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-v">NamedArray</span>(<span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">10</span>), <span class="pl-s">"range_10"</span>)
<span class="pl-en">print</span> (<span class="pl-v">Z</span>.<span class="pl-s1">name</span>)</pre></div>
<h4><a id="user-content-64-consider-a-given-vector-how-to-add-1-to-each-element-indexed-by-a-second-vector-be-careful-with-repeated-indices-" class="anchor" aria-hidden="true" href="#64-consider-a-given-vector-how-to-add-1-to-each-element-indexed-by-a-second-vector-be-careful-with-repeated-indices-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>64. Consider a given vector, how to add 1 to each element indexed by a second vector (be careful with repeated indices)? (★★★)</h4>
<p><code>hint: np.bincount | np.add.at</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Brett Olsen</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-c1">10</span>)
<span class="pl-v">I</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-en">len</span>(<span class="pl-v">Z</span>),<span class="pl-c1">20</span>)
<span class="pl-v">Z</span> <span class="pl-c1">+=</span> <span class="pl-s1">np</span>.<span class="pl-en">bincount</span>(<span class="pl-v">I</span>, <span class="pl-s1">minlength</span><span class="pl-c1">=</span><span class="pl-en">len</span>(<span class="pl-v">Z</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)

<span class="pl-c"># Another solution</span>
<span class="pl-c"># Author: Bartosz Telenczuk</span>
<span class="pl-s1">np</span>.<span class="pl-s1">add</span>.<span class="pl-en">at</span>(<span class="pl-v">Z</span>, <span class="pl-v">I</span>, <span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-65-how-to-accumulate-elements-of-a-vector-x-to-an-array-f-based-on-an-index-list-i-" class="anchor" aria-hidden="true" href="#65-how-to-accumulate-elements-of-a-vector-x-to-an-array-f-based-on-an-index-list-i-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>65. How to accumulate elements of a vector (X) to an array (F) based on an index list (I)? (★★★)</h4>
<p><code>hint: np.bincount</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Alan G Isaac</span>

<span class="pl-v">X</span> <span class="pl-c1">=</span> [<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">3</span>,<span class="pl-c1">4</span>,<span class="pl-c1">5</span>,<span class="pl-c1">6</span>]
<span class="pl-v">I</span> <span class="pl-c1">=</span> [<span class="pl-c1">1</span>,<span class="pl-c1">3</span>,<span class="pl-c1">9</span>,<span class="pl-c1">3</span>,<span class="pl-c1">4</span>,<span class="pl-c1">1</span>]
<span class="pl-v">F</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">bincount</span>(<span class="pl-v">I</span>,<span class="pl-v">X</span>)
<span class="pl-en">print</span>(<span class="pl-v">F</span>)</pre></div>
<h4><a id="user-content-66-considering-a-wh3-image-of-dtypeubyte-compute-the-number-of-unique-colors-" class="anchor" aria-hidden="true" href="#66-considering-a-wh3-image-of-dtypeubyte-compute-the-number-of-unique-colors-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>66. Considering a (w,h,3) image of (dtype=ubyte), compute the number of unique colors (★★★)</h4>
<p><code>hint: np.unique</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Nadav Horesh</span>

<span class="pl-s1">w</span>,<span class="pl-s1">h</span> <span class="pl-c1">=</span> <span class="pl-c1">16</span>,<span class="pl-c1">16</span>
<span class="pl-v">I</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,(<span class="pl-s1">h</span>,<span class="pl-s1">w</span>,<span class="pl-c1">3</span>)).<span class="pl-en">astype</span>(<span class="pl-s1">np</span>.<span class="pl-s1">ubyte</span>)
<span class="pl-v">F</span> <span class="pl-c1">=</span> <span class="pl-v">I</span>[...,<span class="pl-c1">0</span>]<span class="pl-c1">*</span><span class="pl-c1">256</span><span class="pl-c1">*</span><span class="pl-c1">256</span> <span class="pl-c1">+</span> <span class="pl-v">I</span>[...,<span class="pl-c1">1</span>]<span class="pl-c1">*</span><span class="pl-c1">256</span> <span class="pl-c1">+</span><span class="pl-v">I</span>[...,<span class="pl-c1">2</span>]
<span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-en">len</span>(<span class="pl-s1">np</span>.<span class="pl-en">unique</span>(<span class="pl-v">F</span>))
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">unique</span>(<span class="pl-v">I</span>))</pre></div>
<h4><a id="user-content-67-considering-a-four-dimensions-array-how-to-get-sum-over-the-last-two-axis-at-once-" class="anchor" aria-hidden="true" href="#67-considering-a-four-dimensions-array-how-to-get-sum-over-the-last-two-axis-at-once-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>67. Considering a four dimensions array, how to get sum over the last two axis at once? (★★★)</h4>
<p><code>hint: sum(axis=(-2,-1))</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">3</span>,<span class="pl-c1">4</span>,<span class="pl-c1">3</span>,<span class="pl-c1">4</span>))
<span class="pl-c"># solution by passing a tuple of axes (introduced in numpy 1.7.0)</span>
<span class="pl-s1">sum</span> <span class="pl-c1">=</span> <span class="pl-v">A</span>.<span class="pl-en">sum</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span>(<span class="pl-c1">-</span><span class="pl-c1">2</span>,<span class="pl-c1">-</span><span class="pl-c1">1</span>))
<span class="pl-en">print</span>(<span class="pl-s1">sum</span>)
<span class="pl-c"># solution by flattening the last two dimensions into one</span>
<span class="pl-c"># (useful for functions that don't accept tuples for axis argument)</span>
<span class="pl-s1">sum</span> <span class="pl-c1">=</span> <span class="pl-v">A</span>.<span class="pl-en">reshape</span>(<span class="pl-v">A</span>.<span class="pl-s1">shape</span>[:<span class="pl-c1">-</span><span class="pl-c1">2</span>] <span class="pl-c1">+</span> (<span class="pl-c1">-</span><span class="pl-c1">1</span>,)).<span class="pl-en">sum</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-s1">sum</span>)</pre></div>
<h4><a id="user-content-68-considering-a-one-dimensional-vector-d-how-to-compute-means-of-subsets-of-d-using-a-vector-s-of-same-size-describing-subset--indices-" class="anchor" aria-hidden="true" href="#68-considering-a-one-dimensional-vector-d-how-to-compute-means-of-subsets-of-d-using-a-vector-s-of-same-size-describing-subset--indices-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>68. Considering a one-dimensional vector D, how to compute means of subsets of D using a vector S of same size describing subset  indices? (★★★)</h4>
<p><code>hint: np.bincount</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jaime Fernández del Río</span>

<span class="pl-v">D</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">100</span>)
<span class="pl-v">S</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,<span class="pl-c1">100</span>)
<span class="pl-v">D_sums</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">bincount</span>(<span class="pl-v">S</span>, <span class="pl-s1">weights</span><span class="pl-c1">=</span><span class="pl-v">D</span>)
<span class="pl-v">D_counts</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">bincount</span>(<span class="pl-v">S</span>)
<span class="pl-v">D_means</span> <span class="pl-c1">=</span> <span class="pl-v">D_sums</span> <span class="pl-c1">/</span> <span class="pl-v">D_counts</span>
<span class="pl-en">print</span>(<span class="pl-v">D_means</span>)

<span class="pl-c"># Pandas solution as a reference due to more intuitive code</span>
<span class="pl-k">import</span> <span class="pl-s1">pandas</span> <span class="pl-k">as</span> <span class="pl-s1">pd</span>
<span class="pl-en">print</span>(<span class="pl-s1">pd</span>.<span class="pl-v">Series</span>(<span class="pl-v">D</span>).<span class="pl-en">groupby</span>(<span class="pl-v">S</span>).<span class="pl-en">mean</span>())</pre></div>
<h4><a id="user-content-69-how-to-get-the-diagonal-of-a-dot-product-" class="anchor" aria-hidden="true" href="#69-how-to-get-the-diagonal-of-a-dot-product-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>69. How to get the diagonal of a dot product? (★★★)</h4>
<p><code>hint: np.diag</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Mathieu Blondel</span>

<span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,(<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,(<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))

<span class="pl-c"># Slow version  </span>
<span class="pl-s1">np</span>.<span class="pl-en">diag</span>(<span class="pl-s1">np</span>.<span class="pl-en">dot</span>(<span class="pl-v">A</span>, <span class="pl-v">B</span>))

<span class="pl-c"># Fast version</span>
<span class="pl-s1">np</span>.<span class="pl-en">sum</span>(<span class="pl-v">A</span> <span class="pl-c1">*</span> <span class="pl-v">B</span>.<span class="pl-v">T</span>, <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)

<span class="pl-c"># Faster version</span>
<span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">"ij,ji-&gt;i"</span>, <span class="pl-v">A</span>, <span class="pl-v">B</span>)</pre></div>
<h4><a id="user-content-70-consider-the-vector-1-2-3-4-5-how-to-build-a-new-vector-with-3-consecutive-zeros-interleaved-between-each-value-" class="anchor" aria-hidden="true" href="#70-consider-the-vector-1-2-3-4-5-how-to-build-a-new-vector-with-3-consecutive-zeros-interleaved-between-each-value-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>70. Consider the vector [1, 2, 3, 4, 5], how to build a new vector with 3 consecutive zeros interleaved between each value? (★★★)</h4>
<p><code>hint: array[::4]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Warren Weckesser</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">3</span>,<span class="pl-c1">4</span>,<span class="pl-c1">5</span>])
<span class="pl-s1">nz</span> <span class="pl-c1">=</span> <span class="pl-c1">3</span>
<span class="pl-v">Z0</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>(<span class="pl-en">len</span>(<span class="pl-v">Z</span>) <span class="pl-c1">+</span> (<span class="pl-en">len</span>(<span class="pl-v">Z</span>)<span class="pl-c1">-</span><span class="pl-c1">1</span>)<span class="pl-c1">*</span>(<span class="pl-s1">nz</span>))
<span class="pl-v">Z0</span>[::<span class="pl-s1">nz</span><span class="pl-c1">+</span><span class="pl-c1">1</span>] <span class="pl-c1">=</span> <span class="pl-v">Z</span>
<span class="pl-en">print</span>(<span class="pl-v">Z0</span>)</pre></div>
<h4><a id="user-content-71-consider-an-array-of-dimension-553-how-to-mulitply-it-by-an-array-with-dimensions-55-" class="anchor" aria-hidden="true" href="#71-consider-an-array-of-dimension-553-how-to-mulitply-it-by-an-array-with-dimensions-55-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>71. Consider an array of dimension (5,5,3), how to mulitply it by an array with dimensions (5,5)? (★★★)</h4>
<p><code>hint: array[:, :, None]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>,<span class="pl-c1">3</span>))
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-c1">2</span><span class="pl-c1">*</span><span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">5</span>,<span class="pl-c1">5</span>))
<span class="pl-en">print</span>(<span class="pl-v">A</span> <span class="pl-c1">*</span> <span class="pl-v">B</span>[:,:,<span class="pl-c1">None</span>])</pre></div>
<h4><a id="user-content-72-how-to-swap-two-rows-of-an-array-" class="anchor" aria-hidden="true" href="#72-how-to-swap-two-rows-of-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>72. How to swap two rows of an array? (★★★)</h4>
<p><code>hint: array[[]] = array[[]]</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Eelco Hoogendoorn</span>

<span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">25</span>).<span class="pl-en">reshape</span>(<span class="pl-c1">5</span>,<span class="pl-c1">5</span>)
<span class="pl-v">A</span>[[<span class="pl-c1">0</span>,<span class="pl-c1">1</span>]] <span class="pl-c1">=</span> <span class="pl-v">A</span>[[<span class="pl-c1">1</span>,<span class="pl-c1">0</span>]]
<span class="pl-en">print</span>(<span class="pl-v">A</span>)</pre></div>
<h4><a id="user-content-73-consider-a-set-of-10-triplets-describing-10-triangles-with-shared-vertices-find-the-set-of-unique-line-segments-composing-all-the--triangles-" class="anchor" aria-hidden="true" href="#73-consider-a-set-of-10-triplets-describing-10-triangles-with-shared-vertices-find-the-set-of-unique-line-segments-composing-all-the--triangles-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>73. Consider a set of 10 triplets describing 10 triangles (with shared vertices), find the set of unique line segments composing all the  triangles (★★★)</h4>
<p><code>hint: repeat, np.roll, np.sort, view, np.unique</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Nicolas P. Rougier</span>

<span class="pl-s1">faces</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">100</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">3</span>))
<span class="pl-v">F</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">roll</span>(<span class="pl-s1">faces</span>.<span class="pl-en">repeat</span>(<span class="pl-c1">2</span>,<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>),<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
<span class="pl-v">F</span> <span class="pl-c1">=</span> <span class="pl-v">F</span>.<span class="pl-en">reshape</span>(<span class="pl-en">len</span>(<span class="pl-v">F</span>)<span class="pl-c1">*</span><span class="pl-c1">3</span>,<span class="pl-c1">2</span>)
<span class="pl-v">F</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">sort</span>(<span class="pl-v">F</span>,<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
<span class="pl-v">G</span> <span class="pl-c1">=</span> <span class="pl-v">F</span>.<span class="pl-en">view</span>( <span class="pl-s1">dtype</span><span class="pl-c1">=</span>[(<span class="pl-s">'p0'</span>,<span class="pl-v">F</span>.<span class="pl-s1">dtype</span>),(<span class="pl-s">'p1'</span>,<span class="pl-v">F</span>.<span class="pl-s1">dtype</span>)] )
<span class="pl-v">G</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">unique</span>(<span class="pl-v">G</span>)
<span class="pl-en">print</span>(<span class="pl-v">G</span>)</pre></div>
<h4><a id="user-content-74-given-an-array-c-that-is-a-bincount-how-to-produce-an-array-a-such-that-npbincounta--c-" class="anchor" aria-hidden="true" href="#74-given-an-array-c-that-is-a-bincount-how-to-produce-an-array-a-such-that-npbincounta--c-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>74. Given an array C that is a bincount, how to produce an array A such that np.bincount(A) == C? (★★★)</h4>
<p><code>hint: np.repeat</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jaime Fernández del Río</span>

<span class="pl-v">C</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">bincount</span>([<span class="pl-c1">1</span>,<span class="pl-c1">1</span>,<span class="pl-c1">2</span>,<span class="pl-c1">3</span>,<span class="pl-c1">4</span>,<span class="pl-c1">4</span>,<span class="pl-c1">6</span>])
<span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">repeat</span>(<span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-en">len</span>(<span class="pl-v">C</span>)), <span class="pl-v">C</span>)
<span class="pl-en">print</span>(<span class="pl-v">A</span>)</pre></div>
<h4><a id="user-content-75-how-to-compute-averages-using-a-sliding-window-over-an-array-" class="anchor" aria-hidden="true" href="#75-how-to-compute-averages-using-a-sliding-window-over-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>75. How to compute averages using a sliding window over an array? (★★★)</h4>
<p><code>hint: np.cumsum</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jaime Fernández del Río</span>

<span class="pl-k">def</span> <span class="pl-en">moving_average</span>(<span class="pl-s1">a</span>, <span class="pl-s1">n</span><span class="pl-c1">=</span><span class="pl-c1">3</span>) :
    <span class="pl-s1">ret</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">cumsum</span>(<span class="pl-s1">a</span>, <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">float</span>)
    <span class="pl-s1">ret</span>[<span class="pl-s1">n</span>:] <span class="pl-c1">=</span> <span class="pl-s1">ret</span>[<span class="pl-s1">n</span>:] <span class="pl-c1">-</span> <span class="pl-s1">ret</span>[:<span class="pl-c1">-</span><span class="pl-s1">n</span>]
    <span class="pl-k">return</span> <span class="pl-s1">ret</span>[<span class="pl-s1">n</span> <span class="pl-c1">-</span> <span class="pl-c1">1</span>:] <span class="pl-c1">/</span> <span class="pl-s1">n</span>
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">20</span>)
<span class="pl-en">print</span>(<span class="pl-en">moving_average</span>(<span class="pl-v">Z</span>, <span class="pl-s1">n</span><span class="pl-c1">=</span><span class="pl-c1">3</span>))</pre></div>
<h4><a id="user-content-76-consider-a-one-dimensional-array-z-build-a-two-dimensional-array-whose-first-row-is-z0z1z2-and-each-subsequent-row-is--shifted-by-1-last-row-should-be-z-3z-2z-1-" class="anchor" aria-hidden="true" href="#76-consider-a-one-dimensional-array-z-build-a-two-dimensional-array-whose-first-row-is-z0z1z2-and-each-subsequent-row-is--shifted-by-1-last-row-should-be-z-3z-2z-1-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>76. Consider a one-dimensional array Z, build a two-dimensional array whose first row is (Z[0],Z[1],Z[2]) and each subsequent row is  shifted by 1 (last row should be (Z[-3],Z[-2],Z[-1]) (★★★)</h4>
<p><code>hint: from numpy.lib import stride_tricks</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Joe Kington / Erik Rigtorp</span>
<span class="pl-k">from</span> <span class="pl-s1">numpy</span>.<span class="pl-s1">lib</span> <span class="pl-k">import</span> <span class="pl-s1">stride_tricks</span>

<span class="pl-k">def</span> <span class="pl-en">rolling</span>(<span class="pl-s1">a</span>, <span class="pl-s1">window</span>):
    <span class="pl-s1">shape</span> <span class="pl-c1">=</span> (<span class="pl-s1">a</span>.<span class="pl-s1">size</span> <span class="pl-c1">-</span> <span class="pl-s1">window</span> <span class="pl-c1">+</span> <span class="pl-c1">1</span>, <span class="pl-s1">window</span>)
    <span class="pl-s1">strides</span> <span class="pl-c1">=</span> (<span class="pl-s1">a</span>.<span class="pl-s1">itemsize</span>, <span class="pl-s1">a</span>.<span class="pl-s1">itemsize</span>)
    <span class="pl-k">return</span> <span class="pl-s1">stride_tricks</span>.<span class="pl-en">as_strided</span>(<span class="pl-s1">a</span>, <span class="pl-s1">shape</span><span class="pl-c1">=</span><span class="pl-s1">shape</span>, <span class="pl-s1">strides</span><span class="pl-c1">=</span><span class="pl-s1">strides</span>)
<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-en">rolling</span>(<span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">10</span>), <span class="pl-c1">3</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-77-how-to-negate-a-boolean-or-to-change-the-sign-of-a-float-inplace-" class="anchor" aria-hidden="true" href="#77-how-to-negate-a-boolean-or-to-change-the-sign-of-a-float-inplace-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>77. How to negate a boolean, or to change the sign of a float inplace? (★★★)</h4>
<p><code>hint: np.logical_not, np.negative</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Nathaniel J. Smith</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,<span class="pl-c1">100</span>)
<span class="pl-s1">np</span>.<span class="pl-en">logical_not</span>(<span class="pl-v">Z</span>, <span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">Z</span>)

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">1.0</span>,<span class="pl-c1">1.0</span>,<span class="pl-c1">100</span>)
<span class="pl-s1">np</span>.<span class="pl-en">negative</span>(<span class="pl-v">Z</span>, <span class="pl-s1">out</span><span class="pl-c1">=</span><span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-78-consider-2-sets-of-points-p0p1-describing-lines-2d-and-a-point-p-how-to-compute-distance-from-p-to-each-line-i-p0ip1i-" class="anchor" aria-hidden="true" href="#78-consider-2-sets-of-points-p0p1-describing-lines-2d-and-a-point-p-how-to-compute-distance-from-p-to-each-line-i-p0ip1i-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>78. Consider 2 sets of points P0,P1 describing lines (2d) and a point p, how to compute distance from p to each line i (P0[i],P1[i])? (★★★)</h4>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">def</span> <span class="pl-en">distance</span>(<span class="pl-v">P0</span>, <span class="pl-v">P1</span>, <span class="pl-s1">p</span>):
    <span class="pl-v">T</span> <span class="pl-c1">=</span> <span class="pl-v">P1</span> <span class="pl-c1">-</span> <span class="pl-v">P0</span>
    <span class="pl-v">L</span> <span class="pl-c1">=</span> (<span class="pl-v">T</span><span class="pl-c1">**</span><span class="pl-c1">2</span>).<span class="pl-en">sum</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
    <span class="pl-v">U</span> <span class="pl-c1">=</span> <span class="pl-c1">-</span>((<span class="pl-v">P0</span>[:,<span class="pl-c1">0</span>]<span class="pl-c1">-</span><span class="pl-s1">p</span>[...,<span class="pl-c1">0</span>])<span class="pl-c1">*</span><span class="pl-v">T</span>[:,<span class="pl-c1">0</span>] <span class="pl-c1">+</span> (<span class="pl-v">P0</span>[:,<span class="pl-c1">1</span>]<span class="pl-c1">-</span><span class="pl-s1">p</span>[...,<span class="pl-c1">1</span>])<span class="pl-c1">*</span><span class="pl-v">T</span>[:,<span class="pl-c1">1</span>]) <span class="pl-c1">/</span> <span class="pl-v">L</span>
    <span class="pl-v">U</span> <span class="pl-c1">=</span> <span class="pl-v">U</span>.<span class="pl-en">reshape</span>(<span class="pl-en">len</span>(<span class="pl-v">U</span>),<span class="pl-c1">1</span>)
    <span class="pl-v">D</span> <span class="pl-c1">=</span> <span class="pl-v">P0</span> <span class="pl-c1">+</span> <span class="pl-v">U</span><span class="pl-c1">*</span><span class="pl-v">T</span> <span class="pl-c1">-</span> <span class="pl-s1">p</span>
    <span class="pl-k">return</span> <span class="pl-s1">np</span>.<span class="pl-en">sqrt</span>((<span class="pl-v">D</span><span class="pl-c1">**</span><span class="pl-c1">2</span>).<span class="pl-en">sum</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>))

<span class="pl-v">P0</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-v">P1</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-s1">p</span>  <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>,<span class="pl-c1">10</span>,( <span class="pl-c1">1</span>,<span class="pl-c1">2</span>))
<span class="pl-en">print</span>(<span class="pl-en">distance</span>(<span class="pl-v">P0</span>, <span class="pl-v">P1</span>, <span class="pl-s1">p</span>))</pre></div>
<h4><a id="user-content-79-consider-2-sets-of-points-p0p1-describing-lines-2d-and-a-set-of-points-p-how-to-compute-distance-from-each-point-j-pj-to-each-line-i-p0ip1i-" class="anchor" aria-hidden="true" href="#79-consider-2-sets-of-points-p0p1-describing-lines-2d-and-a-set-of-points-p-how-to-compute-distance-from-each-point-j-pj-to-each-line-i-p0ip1i-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>79. Consider 2 sets of points P0,P1 describing lines (2d) and a set of points P, how to compute distance from each point j (P[j]) to each line i (P0[i],P1[i])? (★★★)</h4>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Italmassov Kuanysh</span>

<span class="pl-c"># based on distance function from previous question</span>
<span class="pl-v">P0</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>, <span class="pl-c1">10</span>, (<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-v">P1</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-s1">p</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">-</span><span class="pl-c1">10</span>, <span class="pl-c1">10</span>, (<span class="pl-c1">10</span>,<span class="pl-c1">2</span>))
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-en">distance</span>(<span class="pl-v">P0</span>,<span class="pl-v">P1</span>,<span class="pl-s1">p_i</span>) <span class="pl-k">for</span> <span class="pl-s1">p_i</span> <span class="pl-c1">in</span> <span class="pl-s1">p</span>]))</pre></div>
<h4><a id="user-content-80-consider-an-arbitrary-array-write-a-function-that-extract-a-subpart-with-a-fixed-shape-and-centered-on-a-given-element-pad-with-a-fill-value-when-necessary-" class="anchor" aria-hidden="true" href="#80-consider-an-arbitrary-array-write-a-function-that-extract-a-subpart-with-a-fixed-shape-and-centered-on-a-given-element-pad-with-a-fill-value-when-necessary-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>80. Consider an arbitrary array, write a function that extract a subpart with a fixed shape and centered on a given element (pad with a <code>fill</code> value when necessary) (★★★)</h4>
<p><code>hint: minimum maximum</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Nicolas Rougier</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-s1">shape</span> <span class="pl-c1">=</span> (<span class="pl-c1">5</span>,<span class="pl-c1">5</span>)
<span class="pl-s1">fill</span>  <span class="pl-c1">=</span> <span class="pl-c1">0</span>
<span class="pl-s1">position</span> <span class="pl-c1">=</span> (<span class="pl-c1">1</span>,<span class="pl-c1">1</span>)

<span class="pl-v">R</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>(<span class="pl-s1">shape</span>, <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-v">Z</span>.<span class="pl-s1">dtype</span>)<span class="pl-c1">*</span><span class="pl-s1">fill</span>
<span class="pl-v">P</span>  <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-en">list</span>(<span class="pl-s1">position</span>)).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)
<span class="pl-v">Rs</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-en">list</span>(<span class="pl-v">R</span>.<span class="pl-s1">shape</span>)).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)
<span class="pl-v">Zs</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-en">list</span>(<span class="pl-v">Z</span>.<span class="pl-s1">shape</span>)).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)

<span class="pl-v">R_start</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros</span>((<span class="pl-en">len</span>(<span class="pl-s1">shape</span>),)).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)
<span class="pl-v">R_stop</span>  <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-en">list</span>(<span class="pl-s1">shape</span>)).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)
<span class="pl-v">Z_start</span> <span class="pl-c1">=</span> (<span class="pl-v">P</span><span class="pl-c1">-</span><span class="pl-v">Rs</span><span class="pl-c1">//</span><span class="pl-c1">2</span>)
<span class="pl-v">Z_stop</span>  <span class="pl-c1">=</span> (<span class="pl-v">P</span><span class="pl-c1">+</span><span class="pl-v">Rs</span><span class="pl-c1">//</span><span class="pl-c1">2</span>)<span class="pl-c1">+</span><span class="pl-v">Rs</span><span class="pl-c1">%</span><span class="pl-c1">2</span>

<span class="pl-v">R_start</span> <span class="pl-c1">=</span> (<span class="pl-v">R_start</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-en">minimum</span>(<span class="pl-v">Z_start</span>,<span class="pl-c1">0</span>)).<span class="pl-en">tolist</span>()
<span class="pl-v">Z_start</span> <span class="pl-c1">=</span> (<span class="pl-s1">np</span>.<span class="pl-en">maximum</span>(<span class="pl-v">Z_start</span>,<span class="pl-c1">0</span>)).<span class="pl-en">tolist</span>()
<span class="pl-v">R_stop</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">maximum</span>(<span class="pl-v">R_start</span>, (<span class="pl-v">R_stop</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-en">maximum</span>(<span class="pl-v">Z_stop</span><span class="pl-c1">-</span><span class="pl-v">Zs</span>,<span class="pl-c1">0</span>))).<span class="pl-en">tolist</span>()
<span class="pl-v">Z_stop</span> <span class="pl-c1">=</span> (<span class="pl-s1">np</span>.<span class="pl-en">minimum</span>(<span class="pl-v">Z_stop</span>,<span class="pl-v">Zs</span>)).<span class="pl-en">tolist</span>()

<span class="pl-s1">r</span> <span class="pl-c1">=</span> [<span class="pl-en">slice</span>(<span class="pl-s1">start</span>,<span class="pl-s1">stop</span>) <span class="pl-k">for</span> <span class="pl-s1">start</span>,<span class="pl-s1">stop</span> <span class="pl-c1">in</span> <span class="pl-en">zip</span>(<span class="pl-v">R_start</span>,<span class="pl-v">R_stop</span>)]
<span class="pl-s1">z</span> <span class="pl-c1">=</span> [<span class="pl-en">slice</span>(<span class="pl-s1">start</span>,<span class="pl-s1">stop</span>) <span class="pl-k">for</span> <span class="pl-s1">start</span>,<span class="pl-s1">stop</span> <span class="pl-c1">in</span> <span class="pl-en">zip</span>(<span class="pl-v">Z_start</span>,<span class="pl-v">Z_stop</span>)]
<span class="pl-v">R</span>[<span class="pl-s1">r</span>] <span class="pl-c1">=</span> <span class="pl-v">Z</span>[<span class="pl-s1">z</span>]
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)
<span class="pl-en">print</span>(<span class="pl-v">R</span>)</pre></div>
<h4><a id="user-content-81-consider-an-array-z--1234567891011121314-how-to-generate-an-array-r--1234-2345-3456--11121314-" class="anchor" aria-hidden="true" href="#81-consider-an-array-z--1234567891011121314-how-to-generate-an-array-r--1234-2345-3456--11121314-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>81. Consider an array Z = [1,2,3,4,5,6,7,8,9,10,11,12,13,14], how to generate an array R = [[1,2,3,4], [2,3,4,5], [3,4,5,6], ..., [11,12,13,14]]? (★★★)</h4>
<p><code>hint: stride_tricks.as_strided</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Stefan van der Walt</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">1</span>,<span class="pl-c1">15</span>,<span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">np</span>.<span class="pl-s1">uint32</span>)
<span class="pl-v">R</span> <span class="pl-c1">=</span> <span class="pl-s1">stride_tricks</span>.<span class="pl-en">as_strided</span>(<span class="pl-v">Z</span>,(<span class="pl-c1">11</span>,<span class="pl-c1">4</span>),(<span class="pl-c1">4</span>,<span class="pl-c1">4</span>))
<span class="pl-en">print</span>(<span class="pl-v">R</span>)</pre></div>
<h4><a id="user-content-82-compute-a-matrix-rank-" class="anchor" aria-hidden="true" href="#82-compute-a-matrix-rank-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>82. Compute a matrix rank (★★★)</h4>
<p><code>hint: np.linalg.svd</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Stefan van der Walt</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-v">U</span>, <span class="pl-v">S</span>, <span class="pl-v">V</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">linalg</span>.<span class="pl-en">svd</span>(<span class="pl-v">Z</span>) <span class="pl-c"># Singular Value Decomposition</span>
<span class="pl-s1">rank</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">sum</span>(<span class="pl-v">S</span> <span class="pl-c1">&gt;</span> <span class="pl-c1">1e-10</span>)
<span class="pl-en">print</span>(<span class="pl-s1">rank</span>)</pre></div>
<h4><a id="user-content-83-how-to-find-the-most-frequent-value-in-an-array" class="anchor" aria-hidden="true" href="#83-how-to-find-the-most-frequent-value-in-an-array"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>83. How to find the most frequent value in an array?</h4>
<p><code>hint: np.bincount, argmax</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,<span class="pl-c1">50</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">bincount</span>(<span class="pl-v">Z</span>).<span class="pl-en">argmax</span>())</pre></div>
<h4><a id="user-content-84-extract-all-the-contiguous-3x3-blocks-from-a-random-10x10-matrix-" class="anchor" aria-hidden="true" href="#84-extract-all-the-contiguous-3x3-blocks-from-a-random-10x10-matrix-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>84. Extract all the contiguous 3x3 blocks from a random 10x10 matrix (★★★)</h4>
<p><code>hint: stride_tricks.as_strided</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Chris Barker</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">5</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">10</span>))
<span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">3</span>
<span class="pl-s1">i</span> <span class="pl-c1">=</span> <span class="pl-c1">1</span> <span class="pl-c1">+</span> (<span class="pl-v">Z</span>.<span class="pl-s1">shape</span>[<span class="pl-c1">0</span>]<span class="pl-c1">-</span><span class="pl-c1">3</span>)
<span class="pl-s1">j</span> <span class="pl-c1">=</span> <span class="pl-c1">1</span> <span class="pl-c1">+</span> (<span class="pl-v">Z</span>.<span class="pl-s1">shape</span>[<span class="pl-c1">1</span>]<span class="pl-c1">-</span><span class="pl-c1">3</span>)
<span class="pl-v">C</span> <span class="pl-c1">=</span> <span class="pl-s1">stride_tricks</span>.<span class="pl-en">as_strided</span>(<span class="pl-v">Z</span>, <span class="pl-s1">shape</span><span class="pl-c1">=</span>(<span class="pl-s1">i</span>, <span class="pl-s1">j</span>, <span class="pl-s1">n</span>, <span class="pl-s1">n</span>), <span class="pl-s1">strides</span><span class="pl-c1">=</span><span class="pl-v">Z</span>.<span class="pl-s1">strides</span> <span class="pl-c1">+</span> <span class="pl-v">Z</span>.<span class="pl-s1">strides</span>)
<span class="pl-en">print</span>(<span class="pl-v">C</span>)</pre></div>
<h4><a id="user-content-85-create-a-2d-array-subclass-such-that-zij--zji-" class="anchor" aria-hidden="true" href="#85-create-a-2d-array-subclass-such-that-zij--zji-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>85. Create a 2D array subclass such that Z[i,j] == Z[j,i] (★★★)</h4>
<p><code>hint: class method</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Eric O. Lebigot</span>
<span class="pl-c"># Note: only works for 2d array and value setting using indices</span>

<span class="pl-k">class</span> <span class="pl-v">Symetric</span>(<span class="pl-s1">np</span>.<span class="pl-s1">ndarray</span>):
    <span class="pl-k">def</span> <span class="pl-en">__setitem__</span>(<span class="pl-s1">self</span>, <span class="pl-s1">index</span>, <span class="pl-s1">value</span>):
        <span class="pl-s1">i</span>,<span class="pl-s1">j</span> <span class="pl-c1">=</span> <span class="pl-s1">index</span>
        <span class="pl-en">super</span>(<span class="pl-v">Symetric</span>, <span class="pl-s1">self</span>).<span class="pl-en">__setitem__</span>((<span class="pl-s1">i</span>,<span class="pl-s1">j</span>), <span class="pl-s1">value</span>)
        <span class="pl-en">super</span>(<span class="pl-v">Symetric</span>, <span class="pl-s1">self</span>).<span class="pl-en">__setitem__</span>((<span class="pl-s1">j</span>,<span class="pl-s1">i</span>), <span class="pl-s1">value</span>)

<span class="pl-k">def</span> <span class="pl-en">symetric</span>(<span class="pl-v">Z</span>):
    <span class="pl-k">return</span> <span class="pl-s1">np</span>.<span class="pl-en">asarray</span>(<span class="pl-v">Z</span> <span class="pl-c1">+</span> <span class="pl-v">Z</span>.<span class="pl-v">T</span> <span class="pl-c1">-</span> <span class="pl-s1">np</span>.<span class="pl-en">diag</span>(<span class="pl-v">Z</span>.<span class="pl-en">diagonal</span>())).<span class="pl-en">view</span>(<span class="pl-v">Symetric</span>)

<span class="pl-v">S</span> <span class="pl-c1">=</span> <span class="pl-en">symetric</span>(<span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">10</span>,(<span class="pl-c1">5</span>,<span class="pl-c1">5</span>)))
<span class="pl-v">S</span>[<span class="pl-c1">2</span>,<span class="pl-c1">3</span>] <span class="pl-c1">=</span> <span class="pl-c1">42</span>
<span class="pl-en">print</span>(<span class="pl-v">S</span>)</pre></div>
<h4><a id="user-content-86-consider-a-set-of-p-matrices-wich-shape-nn-and-a-set-of-p-vectors-with-shape-n1-how-to-compute-the-sum-of-of-the-p-matrix-products-at-once-result-has-shape-n1-" class="anchor" aria-hidden="true" href="#86-consider-a-set-of-p-matrices-wich-shape-nn-and-a-set-of-p-vectors-with-shape-n1-how-to-compute-the-sum-of-of-the-p-matrix-products-at-once-result-has-shape-n1-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>86. Consider a set of p matrices wich shape (n,n) and a set of p vectors with shape (n,1). How to compute the sum of of the p matrix products at once? (result has shape (n,1)) (★★★)</h4>
<p><code>hint: np.tensordot</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Stefan van der Walt</span>

<span class="pl-s1">p</span>, <span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">10</span>, <span class="pl-c1">20</span>
<span class="pl-v">M</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-s1">p</span>,<span class="pl-s1">n</span>,<span class="pl-s1">n</span>))
<span class="pl-v">V</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-s1">p</span>,<span class="pl-s1">n</span>,<span class="pl-c1">1</span>))
<span class="pl-v">S</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">tensordot</span>(<span class="pl-v">M</span>, <span class="pl-v">V</span>, <span class="pl-s1">axes</span><span class="pl-c1">=</span>[[<span class="pl-c1">0</span>, <span class="pl-c1">2</span>], [<span class="pl-c1">0</span>, <span class="pl-c1">1</span>]])
<span class="pl-en">print</span>(<span class="pl-v">S</span>)

<span class="pl-c"># It works, because:</span>
<span class="pl-c"># M is (p,n,n)</span>
<span class="pl-c"># V is (p,n,1)</span>
<span class="pl-c"># Thus, summing over the paired axes 0 and 0 (of M and V independently),</span>
<span class="pl-c"># and 2 and 1, to remain with a (n,1) vector.</span></pre></div>
<h4><a id="user-content-87-consider-a-16x16-array-how-to-get-the-block-sum-block-size-is-4x4-" class="anchor" aria-hidden="true" href="#87-consider-a-16x16-array-how-to-get-the-block-sum-block-size-is-4x4-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>87. Consider a 16x16 array, how to get the block-sum (block size is 4x4)? (★★★)</h4>
<p><code>hint: np.add.reduceat</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Robert Kern</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ones</span>((<span class="pl-c1">16</span>,<span class="pl-c1">16</span>))
<span class="pl-s1">k</span> <span class="pl-c1">=</span> <span class="pl-c1">4</span>
<span class="pl-v">S</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">add</span>.<span class="pl-en">reduceat</span>(<span class="pl-s1">np</span>.<span class="pl-s1">add</span>.<span class="pl-en">reduceat</span>(<span class="pl-v">Z</span>, <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">0</span>, <span class="pl-v">Z</span>.<span class="pl-s1">shape</span>[<span class="pl-c1">0</span>], <span class="pl-s1">k</span>), <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">0</span>),
                                       <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">0</span>, <span class="pl-v">Z</span>.<span class="pl-s1">shape</span>[<span class="pl-c1">1</span>], <span class="pl-s1">k</span>), <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
<span class="pl-en">print</span>(<span class="pl-v">S</span>)</pre></div>
<h4><a id="user-content-88-how-to-implement-the-game-of-life-using-numpy-arrays-" class="anchor" aria-hidden="true" href="#88-how-to-implement-the-game-of-life-using-numpy-arrays-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>88. How to implement the Game of Life using numpy arrays? (★★★)</h4>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Nicolas Rougier</span>

<span class="pl-k">def</span> <span class="pl-en">iterate</span>(<span class="pl-v">Z</span>):
    <span class="pl-c"># Count neighbours</span>
    <span class="pl-v">N</span> <span class="pl-c1">=</span> (<span class="pl-v">Z</span>[<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>,<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>] <span class="pl-c1">+</span> <span class="pl-v">Z</span>[<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>] <span class="pl-c1">+</span> <span class="pl-v">Z</span>[<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>,<span class="pl-c1">2</span>:] <span class="pl-c1">+</span>
         <span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>]                <span class="pl-c1">+</span> <span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">2</span>:] <span class="pl-c1">+</span>
         <span class="pl-v">Z</span>[<span class="pl-c1">2</span>:  ,<span class="pl-c1">0</span>:<span class="pl-c1">-</span><span class="pl-c1">2</span>] <span class="pl-c1">+</span> <span class="pl-v">Z</span>[<span class="pl-c1">2</span>:  ,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>] <span class="pl-c1">+</span> <span class="pl-v">Z</span>[<span class="pl-c1">2</span>:  ,<span class="pl-c1">2</span>:])

    <span class="pl-c"># Apply rules</span>
    <span class="pl-s1">birth</span> <span class="pl-c1">=</span> (<span class="pl-v">N</span><span class="pl-c1">==</span><span class="pl-c1">3</span>) <span class="pl-c1">&amp;</span> (<span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>]<span class="pl-c1">==</span><span class="pl-c1">0</span>)
    <span class="pl-s1">survive</span> <span class="pl-c1">=</span> ((<span class="pl-v">N</span><span class="pl-c1">==</span><span class="pl-c1">2</span>) <span class="pl-c1">|</span> (<span class="pl-v">N</span><span class="pl-c1">==</span><span class="pl-c1">3</span>)) <span class="pl-c1">&amp;</span> (<span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>]<span class="pl-c1">==</span><span class="pl-c1">1</span>)
    <span class="pl-v">Z</span>[...] <span class="pl-c1">=</span> <span class="pl-c1">0</span>
    <span class="pl-v">Z</span>[<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>:<span class="pl-c1">-</span><span class="pl-c1">1</span>][<span class="pl-s1">birth</span> <span class="pl-c1">|</span> <span class="pl-s1">survive</span>] <span class="pl-c1">=</span> <span class="pl-c1">1</span>
    <span class="pl-k">return</span> <span class="pl-v">Z</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,(<span class="pl-c1">50</span>,<span class="pl-c1">50</span>))
<span class="pl-k">for</span> <span class="pl-s1">i</span> <span class="pl-c1">in</span> <span class="pl-en">range</span>(<span class="pl-c1">100</span>): <span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-en">iterate</span>(<span class="pl-v">Z</span>)
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)</pre></div>
<h4><a id="user-content-89-how-to-get-the-n-largest-values-of-an-array-" class="anchor" aria-hidden="true" href="#89-how-to-get-the-n-largest-values-of-an-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>89. How to get the n largest values of an array (★★★)</h4>
<p><code>hint: np.argsort | np.argpartition</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">10000</span>)
<span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">shuffle</span>(<span class="pl-v">Z</span>)
<span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">5</span>

<span class="pl-c"># Slow</span>
<span class="pl-en">print</span> (<span class="pl-v">Z</span>[<span class="pl-s1">np</span>.<span class="pl-en">argsort</span>(<span class="pl-v">Z</span>)[<span class="pl-c1">-</span><span class="pl-s1">n</span>:]])

<span class="pl-c"># Fast</span>
<span class="pl-en">print</span> (<span class="pl-v">Z</span>[<span class="pl-s1">np</span>.<span class="pl-en">argpartition</span>(<span class="pl-c1">-</span><span class="pl-v">Z</span>,<span class="pl-s1">n</span>)[:<span class="pl-s1">n</span>]])</pre></div>
<h4><a id="user-content-90-given-an-arbitrary-number-of-vectors-build-the-cartesian-product-every-combinations-of-every-item-" class="anchor" aria-hidden="true" href="#90-given-an-arbitrary-number-of-vectors-build-the-cartesian-product-every-combinations-of-every-item-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>90. Given an arbitrary number of vectors, build the cartesian product (every combinations of every item) (★★★)</h4>
<p><code>hint: np.indices</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Stefan Van der Walt</span>

<span class="pl-k">def</span> <span class="pl-en">cartesian</span>(<span class="pl-s1">arrays</span>):
    <span class="pl-s1">arrays</span> <span class="pl-c1">=</span> [<span class="pl-s1">np</span>.<span class="pl-en">asarray</span>(<span class="pl-s1">a</span>) <span class="pl-k">for</span> <span class="pl-s1">a</span> <span class="pl-c1">in</span> <span class="pl-s1">arrays</span>]
    <span class="pl-s1">shape</span> <span class="pl-c1">=</span> (<span class="pl-en">len</span>(<span class="pl-s1">x</span>) <span class="pl-k">for</span> <span class="pl-s1">x</span> <span class="pl-c1">in</span> <span class="pl-s1">arrays</span>)

    <span class="pl-s1">ix</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">indices</span>(<span class="pl-s1">shape</span>, <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">int</span>)
    <span class="pl-s1">ix</span> <span class="pl-c1">=</span> <span class="pl-s1">ix</span>.<span class="pl-en">reshape</span>(<span class="pl-en">len</span>(<span class="pl-s1">arrays</span>), <span class="pl-c1">-</span><span class="pl-c1">1</span>).<span class="pl-v">T</span>

    <span class="pl-k">for</span> <span class="pl-s1">n</span>, <span class="pl-s1">arr</span> <span class="pl-c1">in</span> <span class="pl-en">enumerate</span>(<span class="pl-s1">arrays</span>):
        <span class="pl-s1">ix</span>[:, <span class="pl-s1">n</span>] <span class="pl-c1">=</span> <span class="pl-s1">arrays</span>[<span class="pl-s1">n</span>][<span class="pl-s1">ix</span>[:, <span class="pl-s1">n</span>]]

    <span class="pl-k">return</span> <span class="pl-s1">ix</span>

<span class="pl-en">print</span> (<span class="pl-en">cartesian</span>(([<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>], [<span class="pl-c1">4</span>, <span class="pl-c1">5</span>], [<span class="pl-c1">6</span>, <span class="pl-c1">7</span>])))</pre></div>
<h4><a id="user-content-91-how-to-create-a-record-array-from-a-regular-array-" class="anchor" aria-hidden="true" href="#91-how-to-create-a-record-array-from-a-regular-array-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>91. How to create a record array from a regular array? (★★★)</h4>
<p><code>hint: np.core.records.fromarrays</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>([(<span class="pl-s">"Hello"</span>, <span class="pl-c1">2.5</span>, <span class="pl-c1">3</span>),
              (<span class="pl-s">"World"</span>, <span class="pl-c1">3.6</span>, <span class="pl-c1">2</span>)])
<span class="pl-v">R</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">core</span>.<span class="pl-s1">records</span>.<span class="pl-en">fromarrays</span>(<span class="pl-v">Z</span>.<span class="pl-v">T</span>,
                               <span class="pl-s1">names</span><span class="pl-c1">=</span><span class="pl-s">'col1, col2, col3'</span>,
                               <span class="pl-s1">formats</span> <span class="pl-c1">=</span> <span class="pl-s">'S8, f8, i8'</span>)
<span class="pl-en">print</span>(<span class="pl-v">R</span>)</pre></div>
<h4><a id="user-content-92-consider-a-large-vector-z-compute-z-to-the-power-of-3-using-3-different-methods-" class="anchor" aria-hidden="true" href="#92-consider-a-large-vector-z-compute-z-to-the-power-of-3-using-3-different-methods-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>92. Consider a large vector Z, compute Z to the power of 3 using 3 different methods (★★★)</h4>
<p><code>hint: np.power, *, np.einsum</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Ryan G.</span>

<span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">rand</span>(<span class="pl-en">int</span>(<span class="pl-c1">5e7</span>))

<span class="pl-c1">%</span><span class="pl-s1">timeit</span> <span class="pl-s1">np</span>.<span class="pl-en">power</span>(<span class="pl-s1">x</span>,<span class="pl-c1">3</span>)
<span class="pl-c1">%</span><span class="pl-s1">timeit</span> <span class="pl-s1">x</span><span class="pl-c1">*</span><span class="pl-s1">x</span><span class="pl-c1">*</span><span class="pl-s1">x</span>
<span class="pl-c1">%</span><span class="pl-s1">timeit</span> <span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">'i,i,i-&gt;i'</span>,<span class="pl-s1">x</span>,<span class="pl-s1">x</span>,<span class="pl-s1">x</span>)</pre></div>
<h4><a id="user-content-93-consider-two-arrays-a-and-b-of-shape-83-and-22-how-to-find-rows-of-a-that-contain-elements-of-each-row-of-b-regardless-of-the-order-of-the-elements-in-b-" class="anchor" aria-hidden="true" href="#93-consider-two-arrays-a-and-b-of-shape-83-and-22-how-to-find-rows-of-a-that-contain-elements-of-each-row-of-b-regardless-of-the-order-of-the-elements-in-b-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>93. Consider two arrays A and B of shape (8,3) and (2,2). How to find rows of A that contain elements of each row of B regardless of the order of the elements in B? (★★★)</h4>
<p><code>hint: np.where</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Gabe Schwartz</span>

<span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">5</span>,(<span class="pl-c1">8</span>,<span class="pl-c1">3</span>))
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">5</span>,(<span class="pl-c1">2</span>,<span class="pl-c1">2</span>))

<span class="pl-v">C</span> <span class="pl-c1">=</span> (<span class="pl-v">A</span>[..., <span class="pl-s1">np</span>.<span class="pl-s1">newaxis</span>, <span class="pl-s1">np</span>.<span class="pl-s1">newaxis</span>] <span class="pl-c1">==</span> <span class="pl-v">B</span>)
<span class="pl-s1">rows</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">where</span>(<span class="pl-v">C</span>.<span class="pl-en">any</span>((<span class="pl-c1">3</span>,<span class="pl-c1">1</span>)).<span class="pl-en">all</span>(<span class="pl-c1">1</span>))[<span class="pl-c1">0</span>]
<span class="pl-en">print</span>(<span class="pl-s1">rows</span>)</pre></div>
<h4><a id="user-content-94-considering-a-10x3-matrix-extract-rows-with-unequal-values-eg-223-" class="anchor" aria-hidden="true" href="#94-considering-a-10x3-matrix-extract-rows-with-unequal-values-eg-223-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>94. Considering a 10x3 matrix, extract rows with unequal values (e.g. [2,2,3]) (★★★)</h4>
<p><code>No hints provided...</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Robert Kern</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">5</span>,(<span class="pl-c1">10</span>,<span class="pl-c1">3</span>))
<span class="pl-en">print</span>(<span class="pl-v">Z</span>)
<span class="pl-c"># solution for arrays of all dtypes (including string arrays and record arrays)</span>
<span class="pl-v">E</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">all</span>(<span class="pl-v">Z</span>[:,<span class="pl-c1">1</span>:] <span class="pl-c1">==</span> <span class="pl-v">Z</span>[:,:<span class="pl-c1">-</span><span class="pl-c1">1</span>], <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
<span class="pl-v">U</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>[<span class="pl-c1">~</span><span class="pl-v">E</span>]
<span class="pl-en">print</span>(<span class="pl-v">U</span>)
<span class="pl-c"># soluiton for numerical arrays only, will work for any number of columns in Z</span>
<span class="pl-v">U</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>[<span class="pl-v">Z</span>.<span class="pl-en">max</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>) <span class="pl-c1">!=</span> <span class="pl-v">Z</span>.<span class="pl-en">min</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>),:]
<span class="pl-en">print</span>(<span class="pl-v">U</span>)</pre></div>
<h4><a id="user-content-95-convert-a-vector-of-ints-into-a-matrix-binary-representation-" class="anchor" aria-hidden="true" href="#95-convert-a-vector-of-ints-into-a-matrix-binary-representation-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>95. Convert a vector of ints into a matrix binary representation (★★★)</h4>
<p><code>hint: np.unpackbits</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Warren Weckesser</span>

<span class="pl-v">I</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-c1">0</span>, <span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">15</span>, <span class="pl-c1">16</span>, <span class="pl-c1">32</span>, <span class="pl-c1">64</span>, <span class="pl-c1">128</span>])
<span class="pl-v">B</span> <span class="pl-c1">=</span> ((<span class="pl-v">I</span>.<span class="pl-en">reshape</span>(<span class="pl-c1">-</span><span class="pl-c1">1</span>,<span class="pl-c1">1</span>) <span class="pl-c1">&amp;</span> (<span class="pl-c1">2</span><span class="pl-c1">**</span><span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">8</span>))) <span class="pl-c1">!=</span> <span class="pl-c1">0</span>).<span class="pl-en">astype</span>(<span class="pl-s1">int</span>)
<span class="pl-en">print</span>(<span class="pl-v">B</span>[:,::<span class="pl-c1">-</span><span class="pl-c1">1</span>])

<span class="pl-c"># Author: Daniel T. McDonald</span>

<span class="pl-v">I</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">array</span>([<span class="pl-c1">0</span>, <span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">15</span>, <span class="pl-c1">16</span>, <span class="pl-c1">32</span>, <span class="pl-c1">64</span>, <span class="pl-c1">128</span>], <span class="pl-s1">dtype</span><span class="pl-c1">=</span><span class="pl-s1">np</span>.<span class="pl-s1">uint8</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">unpackbits</span>(<span class="pl-v">I</span>[:, <span class="pl-s1">np</span>.<span class="pl-s1">newaxis</span>], <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>))</pre></div>
<h4><a id="user-content-96-given-a-two-dimensional-array-how-to-extract-unique-rows-" class="anchor" aria-hidden="true" href="#96-given-a-two-dimensional-array-how-to-extract-unique-rows-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>96. Given a two dimensional array, how to extract unique rows? (★★★)</h4>
<p><code>hint: np.ascontiguousarray | np.unique</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jaime Fernández del Río</span>

<span class="pl-v">Z</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>,<span class="pl-c1">2</span>,(<span class="pl-c1">6</span>,<span class="pl-c1">3</span>))
<span class="pl-v">T</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">ascontiguousarray</span>(<span class="pl-v">Z</span>).<span class="pl-en">view</span>(<span class="pl-s1">np</span>.<span class="pl-en">dtype</span>((<span class="pl-s1">np</span>.<span class="pl-s1">void</span>, <span class="pl-v">Z</span>.<span class="pl-s1">dtype</span>.<span class="pl-s1">itemsize</span> <span class="pl-c1">*</span> <span class="pl-v">Z</span>.<span class="pl-s1">shape</span>[<span class="pl-c1">1</span>])))
<span class="pl-s1">_</span>, <span class="pl-s1">idx</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">unique</span>(<span class="pl-v">T</span>, <span class="pl-s1">return_index</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)
<span class="pl-s1">uZ</span> <span class="pl-c1">=</span> <span class="pl-v">Z</span>[<span class="pl-s1">idx</span>]
<span class="pl-en">print</span>(<span class="pl-s1">uZ</span>)

<span class="pl-c"># Author: Andreas Kouzelis</span>
<span class="pl-c"># NumPy &gt;= 1.13</span>
<span class="pl-s1">uZ</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">unique</span>(<span class="pl-v">Z</span>, <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">0</span>)
<span class="pl-en">print</span>(<span class="pl-s1">uZ</span>)</pre></div>
<h4><a id="user-content-97-considering-2-vectors-a--b-write-the-einsum-equivalent-of-inner-outer-sum-and-mul-function-" class="anchor" aria-hidden="true" href="#97-considering-2-vectors-a--b-write-the-einsum-equivalent-of-inner-outer-sum-and-mul-function-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>97. Considering 2 vectors A &amp; B, write the einsum equivalent of inner, outer, sum, and mul function (★★★)</h4>
<p><code>hint: np.einsum</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Alex Riley</span>
<span class="pl-c"># Make sure to read: http://ajcr.net/Basic-guide-to-einsum/</span>

<span class="pl-v">A</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">10</span>)
<span class="pl-v">B</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">uniform</span>(<span class="pl-c1">0</span>,<span class="pl-c1">1</span>,<span class="pl-c1">10</span>)

<span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">'i-&gt;'</span>, <span class="pl-v">A</span>)       <span class="pl-c"># np.sum(A)</span>
<span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">'i,i-&gt;i'</span>, <span class="pl-v">A</span>, <span class="pl-v">B</span>) <span class="pl-c"># A * B</span>
<span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">'i,i'</span>, <span class="pl-v">A</span>, <span class="pl-v">B</span>)    <span class="pl-c"># np.inner(A, B)</span>
<span class="pl-s1">np</span>.<span class="pl-en">einsum</span>(<span class="pl-s">'i,j-&gt;ij'</span>, <span class="pl-v">A</span>, <span class="pl-v">B</span>)    <span class="pl-c"># np.outer(A, B)</span></pre></div>
<h4><a id="user-content-98-considering-a-path-described-by-two-vectors-xy-how-to-sample-it-using-equidistant-samples-" class="anchor" aria-hidden="true" href="#98-considering-a-path-described-by-two-vectors-xy-how-to-sample-it-using-equidistant-samples-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>98. Considering a path described by two vectors (X,Y), how to sample it using equidistant samples (★★★)?</h4>
<p><code>hint: np.cumsum, np.interp</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Bas Swinckels</span>

<span class="pl-s1">phi</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">arange</span>(<span class="pl-c1">0</span>, <span class="pl-c1">10</span><span class="pl-c1">*</span><span class="pl-s1">np</span>.<span class="pl-s1">pi</span>, <span class="pl-c1">0.1</span>)
<span class="pl-s1">a</span> <span class="pl-c1">=</span> <span class="pl-c1">1</span>
<span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span><span class="pl-c1">*</span><span class="pl-s1">phi</span><span class="pl-c1">*</span><span class="pl-s1">np</span>.<span class="pl-en">cos</span>(<span class="pl-s1">phi</span>)
<span class="pl-s1">y</span> <span class="pl-c1">=</span> <span class="pl-s1">a</span><span class="pl-c1">*</span><span class="pl-s1">phi</span><span class="pl-c1">*</span><span class="pl-s1">np</span>.<span class="pl-en">sin</span>(<span class="pl-s1">phi</span>)

<span class="pl-s1">dr</span> <span class="pl-c1">=</span> (<span class="pl-s1">np</span>.<span class="pl-en">diff</span>(<span class="pl-s1">x</span>)<span class="pl-c1">**</span><span class="pl-c1">2</span> <span class="pl-c1">+</span> <span class="pl-s1">np</span>.<span class="pl-en">diff</span>(<span class="pl-s1">y</span>)<span class="pl-c1">**</span><span class="pl-c1">2</span>)<span class="pl-c1">**</span><span class="pl-c1">.5</span> <span class="pl-c"># segment lengths</span>
<span class="pl-s1">r</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">zeros_like</span>(<span class="pl-s1">x</span>)
<span class="pl-s1">r</span>[<span class="pl-c1">1</span>:] <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">cumsum</span>(<span class="pl-s1">dr</span>)                <span class="pl-c"># integrate path</span>
<span class="pl-s1">r_int</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">linspace</span>(<span class="pl-c1">0</span>, <span class="pl-s1">r</span>.<span class="pl-en">max</span>(), <span class="pl-c1">200</span>) <span class="pl-c"># regular spaced path</span>
<span class="pl-s1">x_int</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">interp</span>(<span class="pl-s1">r_int</span>, <span class="pl-s1">r</span>, <span class="pl-s1">x</span>)       <span class="pl-c"># integrate path</span>
<span class="pl-s1">y_int</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">interp</span>(<span class="pl-s1">r_int</span>, <span class="pl-s1">r</span>, <span class="pl-s1">y</span>)</pre></div>
<h4><a id="user-content-99-given-an-integer-n-and-a-2d-array-x-select-from-x-the-rows-which-can-be-interpreted-as-draws-from-a-multinomial-distribution-with-n-degrees-ie-the-rows-which-only-contain-integers-and-which-sum-to-n-" class="anchor" aria-hidden="true" href="#99-given-an-integer-n-and-a-2d-array-x-select-from-x-the-rows-which-can-be-interpreted-as-draws-from-a-multinomial-distribution-with-n-degrees-ie-the-rows-which-only-contain-integers-and-which-sum-to-n-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>99. Given an integer n and a 2D array X, select from X the rows which can be interpreted as draws from a multinomial distribution with n degrees, i.e., the rows which only contain integers and which sum to n. (★★★)</h4>
<p><code>hint: np.logical_and.reduce, np.mod</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Evgeni Burovski</span>

<span class="pl-v">X</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">asarray</span>([[<span class="pl-c1">1.0</span>, <span class="pl-c1">0.0</span>, <span class="pl-c1">3.0</span>, <span class="pl-c1">8.0</span>],
                [<span class="pl-c1">2.0</span>, <span class="pl-c1">0.0</span>, <span class="pl-c1">1.0</span>, <span class="pl-c1">1.0</span>],
                [<span class="pl-c1">1.5</span>, <span class="pl-c1">2.5</span>, <span class="pl-c1">1.0</span>, <span class="pl-c1">0.0</span>]])
<span class="pl-s1">n</span> <span class="pl-c1">=</span> <span class="pl-c1">4</span>
<span class="pl-v">M</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">logical_and</span>.<span class="pl-en">reduce</span>(<span class="pl-s1">np</span>.<span class="pl-en">mod</span>(<span class="pl-v">X</span>, <span class="pl-c1">1</span>) <span class="pl-c1">==</span> <span class="pl-c1">0</span>, <span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>)
<span class="pl-v">M</span> &amp;= (<span class="pl-v">X</span>.<span class="pl-en">sum</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">-</span><span class="pl-c1">1</span>) <span class="pl-c1">==</span> <span class="pl-s1">n</span>)
<span class="pl-en">print</span>(<span class="pl-v">X</span>[<span class="pl-v">M</span>])</pre></div>
<h4><a id="user-content-100-compute-bootstrapped-95-confidence-intervals-for-the-mean-of-a-1d-array-x-ie-resample-the-elements-of-an-array-with-replacement-n-times-compute-the-mean-of-each-sample-and-then-compute-percentiles-over-the-means-" class="anchor" aria-hidden="true" href="#100-compute-bootstrapped-95-confidence-intervals-for-the-mean-of-a-1d-array-x-ie-resample-the-elements-of-an-array-with-replacement-n-times-compute-the-mean-of-each-sample-and-then-compute-percentiles-over-the-means-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>100. Compute bootstrapped 95% confidence intervals for the mean of a 1D array X (i.e., resample the elements of an array with replacement N times, compute the mean of each sample, and then compute percentiles over the means). (★★★)</h4>
<p><code>hint: np.percentile</code></p>
<div class="highlight highlight-source-python"><pre><span class="pl-c"># Author: Jessica B. Hamrick</span>

<span class="pl-v">X</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randn</span>(<span class="pl-c1">100</span>) <span class="pl-c"># random 1D array</span>
<span class="pl-v">N</span> <span class="pl-c1">=</span> <span class="pl-c1">1000</span> <span class="pl-c"># number of bootstrap samples</span>
<span class="pl-s1">idx</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-s1">random</span>.<span class="pl-en">randint</span>(<span class="pl-c1">0</span>, <span class="pl-v">X</span>.<span class="pl-s1">size</span>, (<span class="pl-v">N</span>, <span class="pl-v">X</span>.<span class="pl-s1">size</span>))
<span class="pl-s1">means</span> <span class="pl-c1">=</span> <span class="pl-v">X</span>[<span class="pl-s1">idx</span>].<span class="pl-en">mean</span>(<span class="pl-s1">axis</span><span class="pl-c1">=</span><span class="pl-c1">1</span>)
<span class="pl-s1">confint</span> <span class="pl-c1">=</span> <span class="pl-s1">np</span>.<span class="pl-en">percentile</span>(<span class="pl-s1">means</span>, [<span class="pl-c1">2.5</span>, <span class="pl-c1">97.5</span>])
<span class="pl-en">print</span>(<span class="pl-s1">confint</span>)</pre></div>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>

    <div class="Popover anim-scale-in js-tagsearch-popover"
     hidden
     data-tagsearch-url="/rougier/numpy-100/find-symbols"
     data-tagsearch-ref="master"
     data-tagsearch-path="100_Numpy_exercises_with_hints_with_solutions.md"
     data-tagsearch-lang="Python"
     data-hydro-click="{&quot;event_type&quot;:&quot;code_navigation.click_on_symbol&quot;,&quot;payload&quot;:{&quot;action&quot;:&quot;click_on_symbol&quot;,&quot;repository_id&quot;:20206590,&quot;ref&quot;:&quot;master&quot;,&quot;language&quot;:&quot;Python&quot;,&quot;originating_url&quot;:&quot;https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises_with_hints_with_solutions.md&quot;,&quot;user_id&quot;:62483513}}"
     data-hydro-click-hmac="a44c797a823de4b5a17e3d98e73ff46c15b6899b29f6c4068be0191ed99604b6">
  <div class="Popover-message Popover-message--large Popover-message--top-left TagsearchPopover mt-1 mb-4 mx-auto Box box-shadow-large">
    <div class="TagsearchPopover-content js-tagsearch-popover-content overflow-auto" style="will-change:transform;">
    </div>
  </div>
</div>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2020 GitHub, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>

    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>
    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"></path></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" async="async" integrity="sha512-WcQmT2vhcClFVOaaAJV/M+HqsJ2Gq/myvl6F3gCVBxykazXTs+i5fvxncSXwyG1CSfcrqmLFw/R/bmFYzprX2A==" type="application/javascript" id="js-conditional-compat" data-src="https://github.githubassets.com/assets/compat-bootstrap-59c4264f.js"></script>
    <script crossorigin="anonymous" integrity="sha512-Qb7XHcWIafGt8U6FsJrxJqGCgszwjKK1zXv1+fAjIz0HDaYppswlGLxEInNMN2dlMBAZnZNSZL8wAvvhKxYx3A==" type="application/javascript" src="https://github.githubassets.com/assets/environment-bootstrap-41bed71d.js"></script>
    <script crossorigin="anonymous" async="async" integrity="sha512-327XCyOytNBlvvFRes7NYmY/gSME67CreRw+pR2DhNKBfEb2Sv0pe/XkZUSqYYlgGdDnaGIKUAb4oRZBLdKBfw==" type="application/javascript" src="https://github.githubassets.com/assets/vendor-df6ed70b.js"></script>
    <script crossorigin="anonymous" async="async" integrity="sha512-eXpQLpAhVAJMHk7Z0KCmLWkovVfHkwsEb7RddC/hfCt62wuVC8JAZUWiTeScadRGkJBFX6UxgmrE/uhItlLvqA==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-797a502e.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-W5UYmkQ8/XyVD/8xIbAMNduNy2utCipfwBvHn2u3HrdMFvCpOHJr5DcY43xF3S176Gxv4tc9pdVw13aIdQ6wNg==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-5b95189a.js"></script>
    
    
    
  <div class="js-stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 000 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 00.01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"></path></svg>
    <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"></path></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>


  </body>
</html>

