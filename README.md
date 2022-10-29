<!DOCTYPE html>
<html lang="en-US" class="theme-">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>How-To/README.md at main -  How-To - The CDM-Project</title>
	<link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoiVGhlIENETS1Qcm9qZWN0Iiwic2hvcnRfbmFtZSI6IlRoZSBDRE0tUHJvamVjdCIsInN0YXJ0X3VybCI6Imh0dHBzOi8vY2RtLXByb2plY3QuY29tLyIsImljb25zIjpbeyJzcmMiOiJodHRwczovL2NkbS1wcm9qZWN0LmNvbS9hc3NldHMvaW1nL2xvZ28ucG5nIiwidHlwZSI6ImltYWdlL3BuZyIsInNpemVzIjoiNTEyeDUxMiJ9LHsic3JjIjoiaHR0cHM6Ly9jZG0tcHJvamVjdC5jb20vYXNzZXRzL2ltZy9sb2dvLnN2ZyIsInR5cGUiOiJpbWFnZS9zdmcreG1sIiwic2l6ZXMiOiI1MTJ4NTEyIn1dfQ==">
	<meta name="theme-color" content="#6cc644">
	<meta name="default-theme" content="auto">
	<meta name="author" content="CDM-Tools">
	<meta name="description" content="How-To">
	<meta name="keywords" content="go,git,self-hosted,gitea">
	<meta name="referrer" content="no-referrer">


	<link rel="alternate" type="application/atom+xml" title="" href="https://cdm-project.com/CDM-Tools/How-To.atom">
	<link rel="alternate" type="application/rss+xml" title="" href="https://cdm-project.com/CDM-Tools/How-To.rss">

	<link rel="icon" href="/assets/img/favicon.svg" type="image/svg+xml">
	<link rel="alternate icon" href="/assets/img/favicon.png" type="image/png">
	<link rel="stylesheet" href="/assets/css/index.css?v=7ea14c4ca3b4ece8917e08968da69260">
	
<script>
	<!--   -->
	window.addEventListener('error', function(e) {window._globalHandlerErrors=window._globalHandlerErrors||[]; window._globalHandlerErrors.push(e);});
	window.config = {
		appVer: '1.17.1',
		appUrl: 'https:\/\/cdm-project.com\/',
		appSubUrl: '',
		assetUrlPrefix: '\/assets',
		runModeIsProd:  true ,
		customEmojis: {"codeberg":":codeberg:","git":":git:","gitea":":gitea:","github":":github:","gitlab":":gitlab:","gogs":":gogs:"},
		useServiceWorker:  false ,
		csrfToken: 'bKRqmRjxu73CLEheDdFd18fvZBM6MTY2NzA0OTQ3Nzg3NzkyMjUzOQ',
		pageData: {},
		requireTribute:  null ,
		notificationSettings: {"EventSourceUpdateTime":10000,"MaxTimeout":60000,"MinTimeout":10000,"TimeoutStep":10000}, 
		enableTimeTracking:  true ,
		
		mermaidMaxSourceCharacters:  5000 ,
		
		i18n: {
			copy_success: 'Copied!',
			copy_error: 'Copy failed',
			error_occurred: 'An error occurred',
			network_error: 'Network error',
		},
	};
	
	window.config.pageData = window.config.pageData || {};
</script>

	<noscript>
		<style>
			.dropdown:hover > .menu { display: block; }
			.ui.secondary.menu .dropdown.item > .menu { margin-top: 0; }
		</style>
	</noscript>

	
		<meta property="og:title" content="How-To">
		<meta property="og:url" content="https://cdm-project.com/CDM-Tools/How-To">
		
	
	<meta property="og:type" content="object">
	
		<meta property="og:image" content="https://cdm-project.com/avatars/9e34aa34b2ac136fb8230088b2c0ca3a">
	

<meta property="og:site_name" content="The CDM-Project">

	<link rel="stylesheet" href="/assets/css/theme-auto.css?v=7ea14c4ca3b4ece8917e08968da69260">


</head>
<body>
	

	<div class="full height">
		<noscript>This website works better with JavaScript.</noscript>

		

		
			<div class="ui top secondary stackable main menu following bar light no-vertical-tabs">
				<div class="ui container" id="navbar">
	
	
	<div class="item brand" style="justify-content: space-between;">
		<a href="/" aria-label="Home">
			<img class="ui mini image" width="30" height="30" src="/assets/img/logo.svg" alt="Logo" aria-hidden="true">
		</a>
		
		<div class="ui basic icon button mobile-only" id="navbar-expand-toggle">
			<i class="sidebar icon"></i>
		</div>
	</div>

	
		<a class="item " href="/explore/repos">Explore</a>
	

	

	


	
		<a class="item" target="_blank" rel="noopener noreferrer" href="https://docs.gitea.io">Help</a>
		<div class="right stackable menu">
			
			<a class="item" rel="nofollow" href="/user/login?redirect_to=%2fCDM-Tools%2fHow-To%2fsrc%2fbranch%2fmain%2fREADME.md">
				<svg viewBox="0 0 16 16" class="svg octicon-sign-in" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2 2.75C2 1.784 2.784 1 3.75 1h2.5a.75.75 0 0 1 0 1.5h-2.5a.25.25 0 0 0-.25.25v10.5c0 .138.112.25.25.25h2.5a.75.75 0 0 1 0 1.5h-2.5A1.75 1.75 0 0 1 2 13.25V2.75zm6.56 4.5 1.97-1.97a.75.75 0 1 0-1.06-1.06L6.22 7.47a.75.75 0 0 0 0 1.06l3.25 3.25a.75.75 0 1 0 1.06-1.06L8.56 8.75h5.69a.75.75 0 0 0 0-1.5H8.56z"/></svg> Sign In
			</a>
		</div>
	
</div>

			</div>
		



<div class="page-content repository file list ">
	<div class="header-wrapper">

	<div class="ui container">
		<div class="repo-header">
			<div class="repo-title-wrap df fc">
				<div class="repo-title">
					
					
						<div class="repo-icon mr-3">
	
		
			<svg viewBox="0 0 16 16" class="svg octicon-repo" width="32" height="32" aria-hidden="true"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 1 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 0 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 0 1 1-1h8zM5 12.25v3.25a.25.25 0 0 0 .4.2l1.45-1.087a.25.25 0 0 1 .3 0L8.6 15.7a.25.25 0 0 0 .4-.2v-3.25a.25.25 0 0 0-.25-.25h-3.5a.25.25 0 0 0-.25.25z"/></svg>
		
	
</div>

					
					<a href="/CDM-Tools">CDM-Tools</a>
					<div class="mx-2">/</div>
					<a href="/CDM-Tools/How-To">How-To</a>
					<a href="/CDM-Tools/How-To.rss"><i class="ui grey icon tooltip ml-3" data-content="RSS Feed" data-position="top center"><svg viewBox="0 0 16 16" class="svg octicon-rss" width="18" height="18" aria-hidden="true"><path fill-rule="evenodd" d="M2.002 2.725a.75.75 0 0 1 .797-.699C8.79 2.42 13.58 7.21 13.974 13.201a.75.75 0 1 1-1.497.098 10.502 10.502 0 0 0-9.776-9.776.75.75 0 0 1-.7-.798zM2 13a1 1 0 1 1 2 0 1 1 0 0 1-2 0zm.84-5.95a.75.75 0 0 0-.179 1.489c2.509.3 4.5 2.291 4.8 4.8a.75.75 0 1 0 1.49-.178A7.003 7.003 0 0 0 2.838 7.05z"/></svg></i></a>
					<div class="labels df ac fw">
						
							
								
							
						
						
					</div>
				</div>
				
				
				
			</div>
			
				<div class="repo-buttons">
					
					<form method="post" action="/CDM-Tools/How-To/action/watch?redirect_to=%2fCDM-Tools%2fHow-To%2fsrc%2fbranch%2fmain%2fREADME.md">
						<input type="hidden" name="_csrf" value="bKRqmRjxu73CLEheDdFd18fvZBM6MTY2NzA0OTQ3Nzg3NzkyMjUzOQ">
						<div class="ui labeled button tooltip" tabindex="0" data-content="Sign in to watch this repository." data-position="top center">
							<button type="submit" class="ui compact small basic button" disabled>
								<svg viewBox="0 0 16 16" class="svg octicon-eye" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 0 1 0 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 0 1 0-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 0 0 0 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 0 0 0-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"/></svg>Watch
							</button>
							<a class="ui basic label" href="/CDM-Tools/How-To/watchers">
								1
							</a>
						</div>
					</form>
					
						<form method="post" action="/CDM-Tools/How-To/action/star?redirect_to=%2fCDM-Tools%2fHow-To%2fsrc%2fbranch%2fmain%2fREADME.md">
							<input type="hidden" name="_csrf" value="bKRqmRjxu73CLEheDdFd18fvZBM6MTY2NzA0OTQ3Nzg3NzkyMjUzOQ">
							<div class="ui labeled button tooltip" tabindex="0" data-content="Sign in to star this repository." data-position="top center">
								<button type="submit" class="ui compact small basic button" disabled>
									<svg viewBox="0 0 16 16" class="svg octicon-star" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.75.75 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694v.001z"/></svg>Star
								</button>
								<a class="ui basic label" href="/CDM-Tools/How-To/stars">
									0
								</a>
							</div>
						</form>
					
					
						<div class="ui labeled button
							
								tooltip disabled
							"
							
								data-content="Sign in to fork this repository."
							
						data-position="top center" data-variation="tiny" tabindex="0">
							<a class="ui compact small basic button"
								
									
								
							>
								<svg viewBox="0 0 16 16" class="svg octicon-repo-forked" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0zm0 2.122a2.25 2.25 0 1 0-1.5 0v.878A2.25 2.25 0 0 0 5.75 8.5h1.5v2.128a2.251 2.251 0 1 0 1.5 0V8.5h1.5a2.25 2.25 0 0 0 2.25-2.25v-.878a2.25 2.25 0 1 0-1.5 0v.878a.75.75 0 0 1-.75.75h-4.5A.75.75 0 0 1 5 6.25v-.878zm3.75 7.378a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0zm3-8.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5z"/></svg>Fork
							</a>
							<div class="ui small modal" id="fork-repo-modal">
								<svg viewBox="0 0 16 16" class="close inside svg octicon-x" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.75.75 0 1 1 1.06 1.06L9.06 8l3.22 3.22a.75.75 0 1 1-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 0 1-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06z"/></svg>
								<div class="header">
									You&#39;ve already forked How-To
								</div>
								<div class="content tl">
									<div class="ui list">
										
									</div>
									
								</div>
							</div>
							<a class="ui basic label" href="/CDM-Tools/How-To/forks">
								0
							</a>
						</div>
					
				</div>
			
		</div>
	</div>

	<div class="ui tabs container">
		
			<div class="ui tabular stackable menu navbar">
				
				<a class="active item" href="/CDM-Tools/How-To">
					<svg viewBox="0 0 16 16" class="svg octicon-code" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4.72 3.22a.75.75 0 0 1 1.06 1.06L2.06 8l3.72 3.72a.75.75 0 1 1-1.06 1.06L.47 8.53a.75.75 0 0 1 0-1.06l4.25-4.25zm6.56 0a.75.75 0 1 0-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 1 0 1.06 1.06l4.25-4.25a.75.75 0 0 0 0-1.06l-4.25-4.25z"/></svg> Code
				</a>
				

				
					<a class=" item" href="/CDM-Tools/How-To/issues">
						<svg viewBox="0 0 16 16" class="svg octicon-issue-opened" width="16" height="16" aria-hidden="true"><path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/><path fill-rule="evenodd" d="M8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0zM1.5 8a6.5 6.5 0 1 1 13 0 6.5 6.5 0 0 1-13 0z"/></svg> Issues
						
					</a>
				

				

				
					<a class=" item" href="/CDM-Tools/How-To/pulls">
						<svg viewBox="0 0 16 16" class="svg octicon-git-pull-request" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.177 3.073 9.573.677A.25.25 0 0 1 10 .854v4.792a.25.25 0 0 1-.427.177L7.177 3.427a.25.25 0 0 1 0-.354zM3.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122v5.256a2.251 2.251 0 1 1-1.5 0V5.372A2.25 2.25 0 0 1 1.5 3.25zM11 2.5h-1V4h1a1 1 0 0 1 1 1v5.628a2.251 2.251 0 1 0 1.5 0V5A2.5 2.5 0 0 0 11 2.5zm1 10.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0zM3.75 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5z"/></svg> Pull Requests
						
					</a>
				

				
					<a href="/CDM-Tools/How-To/packages" class=" item">
						<svg viewBox="0 0 16 16" class="svg octicon-package" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.878.392a1.75 1.75 0 0 0-1.756 0l-5.25 3.045A1.75 1.75 0 0 0 1 4.951v6.098c0 .624.332 1.2.872 1.514l5.25 3.045a1.75 1.75 0 0 0 1.756 0l5.25-3.045c.54-.313.872-.89.872-1.514V4.951c0-.624-.332-1.2-.872-1.514L8.878.392zM7.875 1.69a.25.25 0 0 1 .25 0l4.63 2.685L8 7.133 3.245 4.375l4.63-2.685zM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432L2.5 5.677zm6.25 8.271 4.625-2.683a.25.25 0 0 0 .125-.216V5.677L8.75 8.432v5.516z"/></svg> Packages
					</a>
				

				
					<a href="/CDM-Tools/How-To/projects" class=" item">
						<svg viewBox="0 0 16 16" class="svg octicon-project" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.75 0A1.75 1.75 0 0 0 0 1.75v12.5C0 15.216.784 16 1.75 16h12.5A1.75 1.75 0 0 0 16 14.25V1.75A1.75 1.75 0 0 0 14.25 0H1.75zM1.5 1.75a.25.25 0 0 1 .25-.25h12.5a.25.25 0 0 1 .25.25v12.5a.25.25 0 0 1-.25.25H1.75a.25.25 0 0 1-.25-.25V1.75zM11.75 3a.75.75 0 0 0-.75.75v7.5a.75.75 0 0 0 1.5 0v-7.5a.75.75 0 0 0-.75-.75zm-8.25.75a.75.75 0 0 1 1.5 0v5.5a.75.75 0 0 1-1.5 0v-5.5zM8 3a.75.75 0 0 0-.75.75v3.5a.75.75 0 0 0 1.5 0v-3.5A.75.75 0 0 0 8 3z"/></svg> Projects
						
					</a>
				

				
				<a class=" item" href="/CDM-Tools/How-To/releases">
					<svg viewBox="0 0 16 16" class="svg octicon-tag" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 0 1 .25-.25h5.025a.25.25 0 0 1 .177.073l6.25 6.25a.25.25 0 0 1 0 .354l-5.025 5.025a.25.25 0 0 1-.354 0l-6.25-6.25a.25.25 0 0 1-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.75 1.75 0 0 1 1 7.775zM6 5a1 1 0 1 0 0 2 1 1 0 0 0 0-2z"/></svg> Releases
					
				</a>
				

				
					<a class=" item" href="/CDM-Tools/How-To/wiki" >
						<svg viewBox="0 0 16 16" class="svg octicon-book" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75V1.75zm8.755 3a2.25 2.25 0 0 1 2.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574z"/></svg> Wiki
					</a>
				

				
					<a class=" item" href="/CDM-Tools/How-To/activity">
						<svg viewBox="0 0 16 16" class="svg octicon-pulse" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M6 2a.75.75 0 0 1 .696.471L10 10.731l1.304-3.26A.75.75 0 0 1 12 7h3.25a.75.75 0 0 1 0 1.5h-2.742l-1.812 4.528a.75.75 0 0 1-1.392 0L6 4.77 4.696 8.03A.75.75 0 0 1 4 8.5H.75a.75.75 0 0 1 0-1.5h2.742l1.812-4.529A.75.75 0 0 1 6 2z"/></svg> Activity
					</a>
				

				

				
			</div>
		
	</div>
	<div class="ui tabs divider"></div>
</div>

	<div class="ui container ">
		



		<div class="ui repo-description">
			<div id="repo-desc">
				
				
				<a class="link" href=""></a>
			</div>
			
		</div>
		<div class="mt-3" id="repo-topics">
		
		
		</div>
		
		<div class="hide" id="validate_prompt">
			<span id="count_prompt">You can not select more than 25 topics</span>
			<span id="format_prompt">Topics must start with a letter or number, can include dashes (&#39;-&#39;) and can be up to 35 characters long.</span>
		</div>
		
		<div class="ui segments repository-summary mt-3">
	<div class="ui segment sub-menu repository-menu">
		<div class="ui two horizontal center link list">
			
				<div class="item">
					<a class="ui" href="/CDM-Tools/How-To/commits/branch/main"><svg viewBox="0 0 16 16" class="svg octicon-history" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.643 3.143.427 1.927A.25.25 0 0 0 0 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 0 0 .177-.427L2.715 4.215a6.5 6.5 0 1 1-1.18 4.458.75.75 0 1 0-1.493.154 8.001 8.001 0 1 0 1.6-5.684zM7.75 4a.75.75 0 0 1 .75.75v2.992l2.028.812a.75.75 0 0 1-.557 1.392l-2.5-1A.75.75 0 0 1 7 8.25v-3.5A.75.75 0 0 1 7.75 4z"/></svg> <b>3</b> Commits</a>
				</div>
				<div class="item">
					<a class="ui" href="/CDM-Tools/How-To/branches"><svg viewBox="0 0 16 16" class="svg octicon-git-branch" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.492 2.492 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25zM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zM3.5 3.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0z"/></svg> <b>1</b> Branch</a>
				</div>
				
					<div class="item">
						<a class="ui" href="/CDM-Tools/How-To/tags"><svg viewBox="0 0 16 16" class="svg octicon-tag" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 0 1 .25-.25h5.025a.25.25 0 0 1 .177.073l6.25 6.25a.25.25 0 0 1 0 .354l-5.025 5.025a.25.25 0 0 1-.354 0l-6.25-6.25a.25.25 0 0 1-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.75 1.75 0 0 1 1 7.775zM6 5a1 1 0 1 0 0 2 1 1 0 0 0 0-2z"/></svg> <b>0</b> Tags</a>
					</div>
				
				<div class="item">
					<span class="ui"><svg viewBox="0 0 16 16" class="svg octicon-database" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 3.5c0-.133.058-.318.282-.55.227-.237.592-.484 1.1-.708C4.899 1.795 6.354 1.5 8 1.5c1.647 0 3.102.295 4.117.742.51.224.874.47 1.101.707.224.233.282.418.282.551 0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 5.205 9.646 5.5 8 5.5c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707-.224-.233-.282-.418-.282-.551zM1 3.5c0-.626.292-1.165.7-1.59.406-.422.956-.767 1.579-1.041C4.525.32 6.195 0 8 0c1.805 0 3.475.32 4.722.869.622.274 1.172.62 1.578 1.04.408.426.7.965.7 1.591v9c0 .626-.292 1.165-.7 1.59-.406.422-.956.767-1.579 1.041C11.476 15.68 9.806 16 8 16c-1.805 0-3.475-.32-4.721-.869-.623-.274-1.173-.62-1.579-1.04-.408-.426-.7-.965-.7-1.591v-9zM2.5 8V5.724c.241.15.503.286.779.407C4.525 6.68 6.195 7 8 7c1.805 0 3.475-.32 4.722-.869.275-.121.537-.257.778-.407V8c0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 9.705 9.646 10 8 10c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707C2.558 8.318 2.5 8.133 2.5 8zm0 2.225V12.5c0 .133.058.318.282.55.227.237.592.484 1.1.708 1.016.447 2.471.742 4.118.742 1.647 0 3.102-.295 4.117-.742.51-.224.874-.47 1.101-.707.224-.233.282-.418.282-.551v-2.275c-.241.15-.503.285-.778.406-1.247.549-2.917.869-4.722.869-1.805 0-3.475-.32-4.721-.869a6.236 6.236 0 0 1-.779-.406z"/></svg> <b>135 KiB</b></span>
				</div>
			
		</div>
	</div>
	
</div>

		<div class="ui stackable secondary menu mobile--margin-between-items mobile--no-negative-margins no-vertical-tabs">
			


<div class="fitted item choose reference mr-1">
	<div class="ui floating filter dropdown custom"
		data-branch-form=""
		data-can-create-branch="false"
		data-no-results="No results found."
		data-set-action="" data-submit-form=""
		data-view-type="branch"
		data-ref-name="main"
		data-branch-url-prefix="/CDM-Tools/How-To/src/branch/"
		data-branch-url-suffix="/README.md"
		data-tag-url-prefix="/CDM-Tools/How-To/src/tag/"
		data-tag-url-suffix="/README.md">
		<div class="ui basic small compact button" @click="menuVisible = !menuVisible" @keyup.enter="menuVisible = !menuVisible">
			<span class="text">
				
					<span :class="{visible: isViewTag}" v-if="isViewTag" v-cloak><svg viewBox="0 0 16 16" class="svg octicon-tag" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 0 1 .25-.25h5.025a.25.25 0 0 1 .177.073l6.25 6.25a.25.25 0 0 1 0 .354l-5.025 5.025a.25.25 0 0 1-.354 0l-6.25-6.25a.25.25 0 0 1-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.75 1.75 0 0 1 1 7.775zM6 5a1 1 0 1 0 0 2 1 1 0 0 0 0-2z"/></svg> Tag:</span>
					<span :class="{visible: isViewBranch}" v-if="isViewBranch" v-cloak><svg viewBox="0 0 16 16" class="svg octicon-git-branch" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.492 2.492 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25zM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zM3.5 3.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0z"/></svg> Branch:</span>
					<span :class="{visible: isViewTree}" v-if="isViewTree" v-cloak><svg viewBox="0 0 16 16" class="svg octicon-git-branch" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.492 2.492 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25zM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zM3.5 3.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0z"/></svg> Tree:</span>
					<strong ref="dropdownRefName">main</strong>
				
			</span>
			<svg viewBox="0 0 16 16" class="dropdown icon svg octicon-triangle-down" width="14" height="14" aria-hidden="true"><path d="m4.427 7.427 3.396 3.396a.25.25 0 0 0 .354 0l3.396-3.396A.25.25 0 0 0 11.396 7H4.604a.25.25 0 0 0-.177.427z"/></svg>
		</div>
		<div class="data" style="display: none" data-mode="branches">
			
				
					<div class="item branch selected" data-url="main">main</div>
				
			
			
				
			
		</div>
		<div class="menu transition" :class="{visible: menuVisible}" v-if="menuVisible" v-cloak>
			<div class="ui icon search input">
				<i class="icon df ac jc m-0"><svg viewBox="0 0 16 16" class="svg octicon-filter" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M.75 3a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5H.75zM3 7.75A.75.75 0 0 1 3.75 7h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 3 7.75zm3 4a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75z"/></svg></i>
				<input name="search" ref="searchField" autocomplete="off" v-model="searchTerm" @keydown="keydown($event)" placeholder="Filter branch or tag...">
			</div>
			
				<div class="header branch-tag-choice">
					<div class="ui grid">
						<div class="two column row">
							<a class="reference column" href="#" @click="createTag = false; mode = 'branches'; focusSearchField()">
								<span class="text" :class="{black: mode == 'branches'}">
									<svg viewBox="0 0 16 16" class="mr-2 svg octicon-git-branch" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.492 2.492 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25zM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zM3.5 3.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0z"/></svg>Branches
								</span>
							</a>
							
								<a class="reference column" href="#" @click="createTag = true; mode = 'tags'; focusSearchField()">
									<span class="text" :class="{black: mode == 'tags'}">
										<svg viewBox="0 0 16 16" class="mr-2 svg octicon-tag" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 0 1 .25-.25h5.025a.25.25 0 0 1 .177.073l6.25 6.25a.25.25 0 0 1 0 .354l-5.025 5.025a.25.25 0 0 1-.354 0l-6.25-6.25a.25.25 0 0 1-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.75 1.75 0 0 1 1 7.775zM6 5a1 1 0 1 0 0 2 1 1 0 0 0 0-2z"/></svg>Tags
									</span>
								</a>
							
						</div>
					</div>
				</div>
			
			<div class="scrolling menu" ref="scrollContainer">
				<div v-for="(item, index) in filteredItems" :key="item.name" class="item" :class="{selected: item.selected, active: active == index}" @click="selectItem(item)" :ref="'listItem' + index">${ item.name }</div>
				<div class="item" v-if="showCreateNewBranch" :class="{active: active == filteredItems.length}" :ref="'listItem' + filteredItems.length">
					<a href="#" @click="createNewBranch()">
						<div v-show="createTag">
							<i class="reference tags icon"></i>
							Create tag <strong>${ searchTerm }</strong>
						</div>
						<div v-show="!createTag">
							<svg viewBox="0 0 16 16" class="svg octicon-git-branch" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zm-2.25.75a2.25 2.25 0 1 1 3 2.122V6A2.5 2.5 0 0 1 10 8.5H6a1 1 0 0 0-1 1v1.128a2.251 2.251 0 1 1-1.5 0V5.372a2.25 2.25 0 1 1 1.5 0v1.836A2.492 2.492 0 0 1 6 7h4a1 1 0 0 0 1-1v-.628A2.25 2.25 0 0 1 9.5 3.25zM4.25 12a.75.75 0 1 0 0 1.5.75.75 0 0 0 0-1.5zM3.5 3.25a.75.75 0 1 1 1.5 0 .75.75 0 0 1-1.5 0z"/></svg>
							Create branch <strong>${ searchTerm }</strong>
						</div>
						<div class="text small">
							
								from &#39;main&#39;
							
						</div>
					</a>
					<form ref="newBranchForm" action="/CDM-Tools/How-To/branches/_new/branch/main" method="post">
						<input type="hidden" name="_csrf" value="bKRqmRjxu73CLEheDdFd18fvZBM6MTY2NzA0OTQ3Nzg3NzkyMjUzOQ">
						<input type="hidden" name="new_branch_name" v-model="searchTerm">
						<input type="hidden" name="create_tag" v-model="createTag">
					</form>
				</div>
			</div>
			<div class="message" v-if="showNoResults">${ noResults }</div>
		</div>
	</div>
</div>

			
			
			
			
				<div class="fitted item"><span class="ui breadcrumb repo-path"><a class="section" href="/CDM-Tools/How-To/src/branch/main" title="How-To">How-To</a><span class="divider">/</span><span class="active section" title="README.md">README.md</span></span></div>
			
			<div class="right fitted item mr-0" id="file-buttons">
				<div class="ui tiny primary buttons">
					
						
						
						
					
					
				</div>

			</div>
			<div class="fitted item">
				
			</div>
			<div class="fitted item">
				
				
			</div>
		</div>
		
			<div class="tab-size-8 non-diff-file-content">
	<h4 class="file-header ui top attached header df ac sb">
		<div class="file-header-left df ac pr-4">
			
				<div class="file-info text grey normal mono">
					
					
					
						<div class="file-info-entry">
							13 KiB
						</div>
					
					
				</div>
			
		</div>
		<div class="file-header-right file-actions df ac">
			
				<div class="ui compact icon buttons two-toggle-buttons">
					<a href="/CDM-Tools/How-To/src/branch/main/README.md?display=source" class="ui mini basic button tooltip " data-content="View Source" data-position="bottom center"><svg viewBox="0 0 16 16" class="svg octicon-code" width="15" height="15" aria-hidden="true"><path fill-rule="evenodd" d="M4.72 3.22a.75.75 0 0 1 1.06 1.06L2.06 8l3.72 3.72a.75.75 0 1 1-1.06 1.06L.47 8.53a.75.75 0 0 1 0-1.06l4.25-4.25zm6.56 0a.75.75 0 1 0-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 1 0 1.06 1.06l4.25-4.25a.75.75 0 0 0 0-1.06l-4.25-4.25z"/></svg></a>
					<a href="/CDM-Tools/How-To/src/branch/main/README.md" class="ui mini basic button tooltip active" data-content="View Rendered" data-position="bottom center"><svg viewBox="0 0 16 16" class="svg octicon-file" width="15" height="15" aria-hidden="true"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h9.5a.25.25 0 0 0 .25-.25V6h-2.75A1.75 1.75 0 0 1 9 4.25V1.5H3.75zm6.75.062V4.25c0 .138.112.25.25.25h2.688a.252.252 0 0 0-.011-.013l-2.914-2.914a.272.272 0 0 0-.013-.011zM2 1.75C2 .784 2.784 0 3.75 0h6.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0 1 13.25 16h-9.5A1.75 1.75 0 0 1 2 14.25V1.75z"/></svg></a>
				</div>
			
			
				<div class="ui buttons mr-2">
					<a class="ui mini basic button" href="/CDM-Tools/How-To/raw/branch/main/README.md">Raw</a>
					
						<a class="ui mini basic button" href="/CDM-Tools/How-To/src/commit/699d68ffe06f4e193dd82be38ea48ffe99140415/README.md">Permalink</a>
					
					
						<a class="ui mini basic button" href="/CDM-Tools/How-To/blame/branch/main/README.md">Blame</a>
					
					<a class="ui mini basic button" href="/CDM-Tools/How-To/commits/branch/main/README.md">History</a>
					
				</div>
				<a download href="/CDM-Tools/How-To/raw/branch/main/README.md"><span class="btn-octicon tooltip" data-content="Download file" data-position="bottom center"><svg viewBox="0 0 16 16" class="svg octicon-download" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.47 10.78a.75.75 0 0 0 1.06 0l3.75-3.75a.75.75 0 0 0-1.06-1.06L8.75 8.44V1.75a.75.75 0 0 0-1.5 0v6.69L4.78 5.97a.75.75 0 0 0-1.06 1.06l3.75 3.75zM3.75 13a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5h-8.5z"/></svg></span></a>
				
					
						<span class="btn-octicon tooltip disabled" data-content="You must fork this repository to make or propose changes to this file." data-position="bottom center"><svg viewBox="0 0 16 16" class="svg octicon-pencil" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.013 1.427a1.75 1.75 0 0 1 2.474 0l1.086 1.086a1.75 1.75 0 0 1 0 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 0 1-.927-.928l.929-3.25a1.75 1.75 0 0 1 .445-.758l8.61-8.61zm1.414 1.06a.25.25 0 0 0-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 0 0 0-.354l-1.086-1.086zM11.189 6.25 9.75 4.81l-6.286 6.287a.25.25 0 0 0-.064.108l-.558 1.953 1.953-.558a.249.249 0 0 0 .108-.064l6.286-6.286z"/></svg></span>
					
					
						<span class="btn-octicon tooltip disabled" data-content="You must have write access to make or propose changes to this file." data-position="bottom center"><svg viewBox="0 0 16 16" class="svg octicon-trash" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M6.5 1.75a.25.25 0 0 1 .25-.25h2.5a.25.25 0 0 1 .25.25V3h-3V1.75zm4.5 0V3h2.25a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5H5V1.75C5 .784 5.784 0 6.75 0h2.5C10.216 0 11 .784 11 1.75zM4.496 6.675a.75.75 0 1 0-1.492.15l.66 6.6A1.75 1.75 0 0 0 5.405 15h5.19c.9 0 1.652-.681 1.741-1.576l.66-6.6a.75.75 0 0 0-1.492-.149l-.66 6.6a.25.25 0 0 1-.249.225h-5.19a.25.25 0 0 1-.249-.225l-.66-6.6z"/></svg></span>
					
				
			
		</div>
	</h4>
	<div class="ui attached table unstackable segment">
		
	


		<div class="file-view markup markdown">
			
				<h1 id="user-content-purpose-of-this-project">Purpose of this project</h1>
<p>Hello everyone! Hope all is good. I&#39;ve spent the past few months scouring pages just to try and get decryption keys for widevine content. There was no clear instructions on the internet and the instructions that are there need pieced togther for a proper result. What I&#39;ve tried to do is condense these fragments down to a cohesive guide for people to follow. If you have any questions feel free to message me on here, my reddit or discord, Contact informatoin can be found on my profile.</p>
<h2 id="user-content-prerequisites">Prerequisites</h2>
<p>I used all the mentioned tools on windows 10 x64</p>
<p><a href="https://go.dev/dl/" title="Golang" rel="nofollow">Golang</a></p>
<p><a href="https://www.python.org/downloads/release/python-3105/" title="Python 3.10.5" rel="nofollow">Python 3.10.5</a> <em>Make sure to check &#34;add to path&#34; option when installing.</em></p>
<p><a href="https://www.droidmirror.com/download/minimal-adb-fastboot-v1-4-3-zip" title="ADB Minimal Install" rel="nofollow">ADB Minimal Install</a> <em>Make sure to choose yes when it asks if you would like to add to path</em></p>
<p>An Android 7-12 device that is able to be rooted.</p>
<h4 id="user-content-tools-used">Tools used</h4>
<p><a href="https://cdm-project.com/CDM-Tools/L3-Dumper" title="Dumper" rel="nofollow">Dumper</a></p>
<p><a href="https://cdm-project.com/CDM-Tools/DumperV2" title="DumperV2" rel="nofollow">DumperV2</a></p>
<p><a href="https://cdm-project.com/CDM-Tools/Downey" title="Downey" rel="nofollow">Downey</a></p>
<h4 id="user-content-optional">Optional</h4>
<p><a href="https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp.exe" title="YT-DLP" rel="nofollow">YT-DLP</a></p>
<p><a href="https://www.bok.net/Bento4/binaries/Bento4-SDK-1-6-0-639.x86_64-microsoft-win32.zip" title="MP4 Decrypt" rel="nofollow">MP4Decrypt</a></p>
<p><a href="https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z" title="ffMPEG" rel="nofollow">ffMPEG</a></p>
<h4 id="user-content-android-devices-i-used">Android devices I used</h4>
<p>DumperV1: <a href="https://www.amazon.com/T95-S1-Android-Amlogic-Ethernet/dp/B07F8X1PQR" title="Truewell T95 S1" rel="nofollow">Truewell T95 S1</a>
Pre-rooted, around $30 USD, multiple user success of dumping keys (myself included), good for those who don&#39;t aren&#39;t technically adept to rooting.</p>
<p>DumperV2: <a href="https://www.walmart.com/ip/onn-Android-TV-4K-UHD-Streaming-Device-with-Voice-Remote-Control-HDMI-Cable/636597403" title="onn. Android TV 4K UHD Streaming Device" rel="nofollow">onn. Android TV 4K UHD Streaming Device</a>
Cheap and accesable but, needs magisk, frida module, and liboemcrypto disabler installed. You can find insturctions and scripts for installing magisk and rooting <a href="https://cdm-project.com/cdm-tools/onn-scripts" title="here" rel="nofollow">here</a>, follow up until step 7 and install the frida-server and liboemcrypto modules below from the magisk app.</p>
<p><strong>IF YOU DO USE YOUR OWN ANDROID DEVICE YOU MUST INSTALL <a href="https://topjohnwu.github.io/Magisk/install.html" title="MAGISK" rel="nofollow">MAGISK</a> AND THE <a href="https://github.com/ViRb3/magisk-frida" title="FRIDA-SERVER MODULE" rel="nofollow">FRIDA-SERVER MODULE</a> OR PUSH THE <a href="https://github.com/frida/frida/releases/download/" title="FRIDA SERVER ANDROID APP" rel="nofollow">FRIDA SERVER ANDROID APP</a> IF YOU DON&#39;T NEED THE LIBOEMCRYPTO DISABLER.</strong></p>
<p><strong>AS MENTIONED IN DUMPER READMES, SOME DEVICES WILL CONTINUE TO USE L1 AFTER ROOT, IF UNSURE USE &#34;DRM INFO&#34;, IF STILL ON L1 PLEASE INSTALL <a href="https://github.com/Magisk-Modules-Repo/liboemcryptodisabler" title="LIBOEMCRYPTO DISABLER" rel="nofollow">LIBOEMCRYPTO DISABLER</a> MAGISK MODULE</strong></p>
<h1 id="user-content-step-1-preparing-cdm">Step 1: Preparing CDM</h1>
<p>Connect to your android device via ADB, on the T95 this is enabled by default over wifi. Other devices may vary.</p>
<p><strong>To enable ADB / USB Debugging follow these steps</strong></p>
<ol>
<li>Open your device&#39;s Settings and tap About phone or About tablet.</li>
<li>Tap Build number repeatedly until you see a notification that reads &#34;You are now a developer.&#34;</li>
<li>Go back to the main System menu, then tap Developer options.</li>
<li>Tap the toggle switch in the top-right corner to enable developer options (if it&#39;s not already enabled).</li>
<li>Tap OK to confirm.</li>
<li>Tap the USB debugging toggle switch.</li>
<li>Tap OK to confirm.</li>
<li>The next time you plug your device into a computer, you&#39;ll receive a prompt asking if you want to authorize USB debugging for that computer. Tap OK to confirm.</li>
</ol>
<p>You may now connect to your device</p>
<p><code>adb connect &lt;device-ip-address&gt;</code>
or if using USB
<code>adb devices</code></p>
<p>On your device you should receive a notificatoin to accept the adb connection, checkmark trust this device and then click allow.</p>
<p><strong>IF YOU HAVE MAGISK-FRIDA MODULE INSTALLED YOU MAY SKIP TO THE NEXT STEP</strong></p>
<p><strong>THIS METHOD <em>MAY</em> BE USED IF YOU ARE RUNNING AT AN L3 LEVEL AND HAVE ROOT ACCESS, THIS IS JUST SPECIFIC FOR THE T95S1</strong></p>
<p>Let&#39;s go ahead and push frida-server to the Android device, for the T95 S1 I used <a href="https://github.com/frida/frida/releases/download/15.1.17/frida-server-15.1.17-android-arm.xz" title="Frida-Server 15.1.17" rel="nofollow">Frida-Server 15.1.17</a> for android. Unnzip the xz file and extract Frida-Server file.</p>
<p>Change directory to where you extracted the file and enter the command <code>adb push frida-server-15.1.17-android-arm /sdcard/</code></p>
<p>Once it has been pushed open up a shell with <code>adb shell</code></p>
<p>Move the server to the tmp directory <code>mv /sdcard/fridaserver-15.1.17-android-arm /data/local/tmp/</code></p>
<p>You may get an error about chown permission, this is negligible</p>
<p>Login as super user and create a new environment <code>su -</code></p>
<p>Give execute privileges to frida-server <code>chmod +x  /data/local/tmp/fridaserver-15.1.17-android-arm</code></p>
<p>Start the server <code>/data/local/tmp/fridaserver-15.1.17-android-arm</code></p>
<p><strong>When you start the server command prompt will hang, this is normal and means the program is running, do not close out and continue to step 2</strong></p>
<h1 id="user-content-step-2-extracting-the-cdm">Step 2: Extracting the CDM</h1>
<p><em>If you would like to check if frida-server is running connect via adb to your device in new command prompt like in step one, then use <code>adb shell</code> and then <code>su</code> and then <code>ps | grep frida</code> this should show you the process running, if it does not something went wrong</em> <strong>NOTE: MAY NOT BE APPLICABLE IF MODULE WAS INSTALLED VIA FRIDA</strong></p>
<p>Download and extract <a href="https://cdm-project.com/CDM-Tools/L3-Dumper" title="Dumper" rel="nofollow">Dumper</a> for android 7-9</p>
<p>Download and extract <a href="https://cdm-project.com/CDM-Tools/DumperV2" title="DumperV2" rel="nofollow">DumperV2</a> for android 10-12</p>
<p>Open a new command prompt as administrator and change directories to the newly extracted folder and run <code>pip3 install -r requirements.txt</code> and once that&#39;s finished, start the program with <code>python dump_keys.py</code></p>
<p>Now play some widevine encrpyed content on your Android device. I suggest using <a href="https://bitmovin.com/demos/drm" title="https://bitmovin.com/demos/drm" rel="nofollow">https://bitmovin.com/demos/drm</a> playing over google chrome.</p>
<p><em>Side note: on the T95 S1 I had to do these specific steps to get it to reliably dump. Play the video on bitmovin, stop dumper, start dumper, wait for it to finish booting, then click on the green &#34;load&#34; button in the top right of bitmovin while the video was still playing, so far this method has worked the best for me</em></p>
<p><em>Side note: on the onn 4k box, I had to install fx file manager and sideload launcher, push a chrome apk, install with the file manager, and run from sideloader, started on a page that wasn&#39;t bitmovin (duckduckgo.com in my case) started the script, loaded bitmovin, clicked the &#34;load&#34; button in the top right corner, stopped the script, started the script again, went back to duckduckgo.com, stopped the script and started repeatedly until you see an RSA fingerprint, when you see that you can go back to butmovin and play the video and dump the keys</em></p>
<p>Once you have played the content your keys should be dumped in the dumper folder under <code>/key-dumps/your-device-keys/xxxx/xxxxxxxx/</code> and should be named <code>client_id.bin</code> and <code>private_key.pem</code></p>
<p>Make a copy of these for safekeeping wherever you like but DO NOT LOSE THEM</p>
<p><em>You can now close out of running frida server if you are running it over adb, you may also close dumper once you have verified successful dumping.</em></p>
<p>Make sure to have file extensions visible on windows, this can be turned on by searching &#34;show file extensions&#34; in the windows search bar.</p>
<p>Now we will rename these files, <code>clent_id.bin</code> to <code>device_client_id_blob.</code> and rename <code>private_key.pem</code> to <code>device_private_key.</code> <strong>The periods on the end is intentional as windows likes to keep file extentions, please make sure to have this exact or it will cause errors with downey! Only rename with windows, using a program such as text editor and saving under all files will still corrupt the data!</strong></p>
<h1 id="user-content-step-3-obtaining-decryption-keys">Step 3: Obtaining decryption keys</h1>
<p>Download and extract <a href="https://cdm-project.com/CDM-Tools/Downey" title="Downey" rel="nofollow">Downey</a></p>
<p>Open a new command prompt as administrator and change directories to the newly extracted folder</p>
<p>Build Downey with command <code>go build -o downey.exe -a main.go</code> once this is finished you should see <code>downeye.exe</code> in your Downey folder</p>
<p>Copy the <code>device_client_id_blob</code> file and <code>device_private_key</code> file to the Downey folder.</p>
<p>Open Firefox or Chrome and navigate back to <a href="https://bitmovin.com/demos/drm" title="https://bitmovin.com/demos/drm" rel="nofollow">https://bitmovin.com/demos/drm</a> and open web devoloper tools (ctrl+shift+c) and click on the network tab</p>
<p>Play the video on the site, then in the filter urls type in <code>method:POST</code> and under the domain look for the licensing server, in this case it&#39;s <code>https://cwip-shaka-proxy.appspot.com/</code> right click on this value and copy value -&gt; copy post data and paste this somewhere safe for now.</p>
<p>Next we need the MPD file, under the filter url section in the network tab now we are going to filter for <code>MPD</code> one result should show up for <code>11331.mpd</code> downoad this by double clicking or copying and saving. Rename this file to <code>manifest.mpd</code>and place it in your Downey folder</p>
<p>Now we have everything we need, let&#39;s go ahead and run downey with <code>downey.exe --lic-server &#34;https://cwip-shaka-proxy.appspot.com/no_auth&#34;</code> if everything goes successful you should get the decryption keys for the video, so for bitmovin i received</p>
<pre class="code-block"><code class="chroma language-text">Decryption keys:
ccbf5fb4c2965be7aa130ffb3ba9fd73:9cc0c92044cb1d69433f5f5839a159df
9bf0e9cf0d7b55aeb4b289a63bab8610:90f52fd8ca48717b21d0c2fed7a12ae1
eb676abbcb345e96bbcf616630f1a3da:100b6c20940f779a4589152b57d2dacb
0294b9599d755de2bbf0fdca3fa5eab7:3bda2f40344c7def614227b9c0f03e26
639da80cf23b55f3b8cab3f64cfa5df6:229f5f29b643e203004b30c4eaf348f4
</code></pre><p>And there you have it! decryption keys for all versions of the video and one for the audio.</p>
<h1 id="user-content-optional-how-to-download-decrypt-and-merge-bitmovin-video-and-audio">Optional: How to download, decrypt, and merge Bitmovin video and audio</h1>
<h3 id="user-content-downloading">Downloading</h3>
<p>Download <a href="https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp.exe" title="YT-DLP" rel="nofollow">YT-DLP</a> and place in a new folder or a folder of your choice.</p>
<p>Open a new command prompt as administrator and change directories to the folder you&#39;ve placed <code>yt-dlp.exe</code></p>
<p>Go back to <a href="https://bitmovin.com/demos/drm" title="https://bitmovin.com/demos/drm" rel="nofollow">https://bitmovin.com/demos/drm</a> and open up the web devoloper tools (ctrl+shift+c) and click on the network tab.</p>
<p>Play the video on the site, then in the filter urls type in <code>MPD</code> like in step 3.</p>
<p>Copy the url value from the search result. You can do this by: Right click -&gt; Copy Value -&gt; Copy URL In this case it should be <code>https://cdn.bitmovin.com/content/assets/art-of-motion_drm/mpds/11331.mpd</code></p>
<p>Now in the command prompt you have opened execute the command <code>yt-dlp.exe --allow-unplayable https://cdn.bitmovin.com/content/assets/art-of-motion_drm/mpds/11331.mpd</code></p>
<p>This should download two files in your yt-dlp directory, an encrpyted <code>mp4</code> video file  and an encrypted <code>m4a</code> audio file. For ease I have renamed these <code>encrypted.mp4</code> and <code>encrypted.m4a</code></p>
<h2 id="user-content-decrypting">Decrypting</h2>
<p>Download and extract <a href="https://www.bok.net/Bento4/binaries/Bento4-SDK-1-6-0-639.x86_64-microsoft-win32.zip" title="MP4 Decrypt" rel="nofollow">MP4Decrypt</a></p>
<p>Open a new command prompt as administrator and change directories to the MP4Decrypt bin folder.</p>
<p>Place your <code>encrpyted.mp4</code> and <code>encrypted.m4a</code> files in this bin folder as well</p>
<p>Decrpyt the video by using <code>mp4decrypt.exe --key xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx inputfile.mp4 outputfile.mp4</code> where the key in this case would be one we extracted earlier, <code>inputfile.mp4</code> being the <code>encrytped.mp4</code> file we downloaded earlier and <code>outputfile.mp4</code> can be named whatever you choose, I will be using <code>decrypted.mp4</code> so for this instance it would be <code>mp4decrypt.exe --key eb676abbcb345e96bbcf616630f1a3da:100b6c20940f779a4589152b57d2dacb encrypted.mp4 decrypted.mp4</code></p>
<p>Decrpyt the audio by using <code>mp4decrypt.exe --key xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx inputfile.m4a outputfile.m4a</code> where the key in this case would be one we extracted earlier, <code>inputfile.m4a</code> being the <code>encrytped.m4a</code> file we downloaded earlier and <code>outputfile.m4a</code> can be named whatever you choose, I will be using <code>decrypted.m4a</code> so for this instance it would be <code>mp4decrypt.exe --key eb676abbcb345e96bbcf616630f1a3da:100b6c20940f779a4589152b57d2dacb encrypted.m4a decrypted.m4a</code></p>
<p>You should now have two playable files, the video <code>decrypted.mp4</code> and the audio <code>decrypted.m4a</code> now it&#39;s time for the final step .</p>
<h3 id="user-content-merging">Merging</h3>
<p>Download and extract <a href="https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z" title="ffMPEG" rel="nofollow">ffMPEG</a></p>
<p>Open a new command prompt as administrator and change directories to the ffmpeg bin folder.</p>
<p>Place your <code>decrpyted.mp4</code> and <code>derypted.m4a</code> files in this bin folder as well</p>
<p>In command prompt issue the command to merge the two streams <code>ffmpeg.exe -i decrypted.mp4 -i decrypted.m4a -vcodec copy -acodec copy bitmovin.mp4</code></p>
<p>Congrats, you now have a playable widevine audio/video file!</p>
<h1 id="user-content-site-specific-instructions">Site Specific instructions.</h1>
<p>Hopefully more to come!</p>
<p><a href="https://cdm-project.com/cdm-tools/hbo-max" title="HBO Max" rel="nofollow">HBO Max</a></p>
<p><a href="https://cdm-project.com/cdm-tools/udemy" title="Udemy" rel="nofollow">Udemy</a></p>
<p><a href="https://cdm-project.com/cdm-tools/hulu" title="Hulu" rel="nofollow">Hulu</a></p>
<p><a href="https://cdm-project.com/cdm-tools/disneyplus" title="Disney+" rel="nofollow">Disney+</a></p>
<h1 id="user-content-don-t-feel-like-rooting-and-dumping-purchase-an-l3-cdm">Don&#39;t feel like rooting and dumping? Purchase an L3 CDM.</h1>
<p>Contact me on my telegram or discord (info found on my gitlab profile)</p>
<p>Selling for $35 USD</p>

			
		</div>
	</div>
</div>

		
	</div>
</div>


	

	</div>

	

	<footer>
	<div class="ui container">
		<div class="ui left">
			Powered by Gitea
			
				Version:
				
					1.17.1
				
			
			
				Page: <strong>18ms</strong>
				Template
				: <strong>1ms</strong>
			
		</div>
		<div class="ui right links">
			
			<div class="ui language bottom floating slide up dropdown link item">
				<svg viewBox="0 0 16 16" class="svg octicon-globe" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.543 7.25h2.733c.144-2.074.866-3.756 1.58-4.948.12-.197.237-.381.353-.552a6.506 6.506 0 0 0-4.666 5.5zm2.733 1.5H1.543a6.506 6.506 0 0 0 4.666 5.5 11.13 11.13 0 0 1-.352-.552c-.715-1.192-1.437-2.874-1.581-4.948zm1.504 0h4.44a9.637 9.637 0 0 1-1.363 4.177c-.306.51-.612.919-.857 1.215a9.978 9.978 0 0 1-.857-1.215A9.637 9.637 0 0 1 5.78 8.75zm4.44-1.5H5.78a9.637 9.637 0 0 1 1.363-4.177c.306-.51.612-.919.857-1.215.245.296.55.705.857 1.215A9.638 9.638 0 0 1 10.22 7.25zm1.504 1.5c-.144 2.074-.866 3.756-1.58 4.948-.12.197-.237.381-.353.552a6.506 6.506 0 0 0 4.666-5.5h-2.733zm2.733-1.5h-2.733c-.144-2.074-.866-3.756-1.58-4.948a11.738 11.738 0 0 0-.353-.552 6.506 6.506 0 0 1 4.666 5.5zM8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0z"/></svg>
				<div class="text">English</div>
				<div class="menu language-menu">
					
						<a lang="id-ID" data-url="/?lang=id-ID" class="item ">Bahasa Indonesia</a>
					
						<a lang="de-DE" data-url="/?lang=de-DE" class="item ">Deutsch</a>
					
						<a lang="en-US" data-url="/?lang=en-US" class="item active selected">English</a>
					
						<a lang="es-ES" data-url="/?lang=es-ES" class="item ">Español</a>
					
						<a lang="fr-FR" data-url="/?lang=fr-FR" class="item ">Français</a>
					
						<a lang="it-IT" data-url="/?lang=it-IT" class="item ">Italiano</a>
					
						<a lang="lv-LV" data-url="/?lang=lv-LV" class="item ">Latviešu</a>
					
						<a lang="hu-HU" data-url="/?lang=hu-HU" class="item ">Magyar nyelv</a>
					
						<a lang="nl-NL" data-url="/?lang=nl-NL" class="item ">Nederlands</a>
					
						<a lang="pl-PL" data-url="/?lang=pl-PL" class="item ">Polski</a>
					
						<a lang="pt-PT" data-url="/?lang=pt-PT" class="item ">Português de Portugal</a>
					
						<a lang="pt-BR" data-url="/?lang=pt-BR" class="item ">Português do Brasil</a>
					
						<a lang="fi-FI" data-url="/?lang=fi-FI" class="item ">Suomi</a>
					
						<a lang="sv-SE" data-url="/?lang=sv-SE" class="item ">Svenska</a>
					
						<a lang="tr-TR" data-url="/?lang=tr-TR" class="item ">Türkçe</a>
					
						<a lang="cs-CZ" data-url="/?lang=cs-CZ" class="item ">Čeština</a>
					
						<a lang="el-GR" data-url="/?lang=el-GR" class="item ">Ελληνικά</a>
					
						<a lang="bg-BG" data-url="/?lang=bg-BG" class="item ">Български</a>
					
						<a lang="ru-RU" data-url="/?lang=ru-RU" class="item ">Русский</a>
					
						<a lang="sr-SP" data-url="/?lang=sr-SP" class="item ">Српски</a>
					
						<a lang="uk-UA" data-url="/?lang=uk-UA" class="item ">Українська</a>
					
						<a lang="fa-IR" data-url="/?lang=fa-IR" class="item ">فارسی</a>
					
						<a lang="ml-IN" data-url="/?lang=ml-IN" class="item ">മലയാളം</a>
					
						<a lang="ja-JP" data-url="/?lang=ja-JP" class="item ">日本語</a>
					
						<a lang="zh-CN" data-url="/?lang=zh-CN" class="item ">简体中文</a>
					
						<a lang="zh-TW" data-url="/?lang=zh-TW" class="item ">繁體中文（台灣）</a>
					
						<a lang="zh-HK" data-url="/?lang=zh-HK" class="item ">繁體中文（香港）</a>
					
						<a lang="ko-KR" data-url="/?lang=ko-KR" class="item ">한국어</a>
					
				</div>
			</div>
			<a href="/assets/js/licenses.txt">Licenses</a>
			<a href="/api/swagger">API</a>
			<a target="_blank" rel="noopener noreferrer" href="https://gitea.io">Website</a>
			
		</div>
	</div>
</footer>




	<script src="/assets/js/index.js?v=7ea14c4ca3b4ece8917e08968da69260" onerror="alert('Failed to load asset files from ' + this.src + ', please make sure the asset files can be accessed and the ROOT_URL setting in app.ini is correct.')"></script>

</body>
</html>

