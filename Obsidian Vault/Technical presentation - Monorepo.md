#nx #monorepo #module_federation #angular_ssr_universal #esbuild #vite #webpack #env_configuration

# Monorepo
	1. Monorepo vs polyrepo vs monolythic
	2. Limitation of our previous migration from xomad-app from theplug-fe
		1. [ ] Cannot resolve cjs modules => useless treeshaking mechanism
		2. DRY
		3. Cannot clean legacy/smell codes
		4. Cannot clean UI framework combination (bootstrap, material, css utilities)aa
	3. Microfrontend in future: multiple frameworks with module federation.
	**=> Solution: need to apply NX to our platform**
# Angular universal
	1. Why we should go with SSR.
		   Wells, idk, we definetely don't have this because our business doesn't need to SEO.
		   improve web vitals at some point.
		   approaching new tech.=
		   Imperimental, (less effort for transforming to CSR if fail)
	1. Hydration.
	2. Which things I need to pay attention when migrating from CSR to SSR
	3. SSR vs CSR pros and cons (web vital)
		1. low TTFB
		2. better FCP; LCP probably
# Source Structure
	# Why do we split into multiple library
	1. Easy to buildable / publishable
	2. Nx graph
5. Why do we need this structure : nartc, recommend from NX, and
	1. Prevent circular DI
	2. Easy buildable, publishable.
# Esbuild + vite + webpack + rollup.
# TDD + BDD
# extra env technique
	1. at build time with env.
	2. at runtime with json fetching
## Document with astro





