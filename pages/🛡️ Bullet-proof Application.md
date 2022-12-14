tags:: #bpa #🛡️bpa

- ## References:
	- [REST APIs must be hypertext-driven » Untangled](https://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven) -* Roy T. Fielding*
	- [software architecture » Untangled](https://roy.gbiv.com/untangled/category/architecture) - Roy T. Fielding
	- [web architecture » Untangled](https://roy.gbiv.com/untangled/category/web-architecture) - Roy T. Fielding
	- [open source » Untangled](https://roy.gbiv.com/untangled/category/opensource) - Roy T. Fielding
	- [standards » Untangled](https://roy.gbiv.com/untangled/category/standards) - Roy T. Fielding
	- [systems engineering » Untangled](https://roy.gbiv.com/untangled/category/systems-engineering) - Roy T. Fielding
	- [RFC 5023 - The Atom Publishing Protocol](https://datatracker.ietf.org/doc/html/rfc5023)
	- [Microformat - Wikipedia](https://en.wikipedia.org/wiki/Microformat)
	- [RFC 5988 - Web Linking](https://datatracker.ietf.org/doc/html/rfc5988)
	-
	-
	-
- ## Tools used
	- Hosting Providers
		- Cloud ✅
			- Linode
			- Digital Ocean
			- Vultr
			- Forge + (Envoyer?)
			-
		- Self Managed VPS ✔️
		- Web hosting ❌
	- The Backend
		- Laravel
		- Appwrite
		- Nhost
		- Supabase
		- Firebase
		- RavenDB
		- FuanaDB
	- The Frontend
		- Flutter
		- Svelte/SvelteKit
		- Laravel Livewire/Inertia
		- Astro
	- Databases
	  collapsed:: true
		- Planet Scale
		- PostgreSQL on  Heroku or any Cloud/Web hosting provider
		- MariaDB on Heroku or any Cloud/Web hosting provider
		- Firebase
		- Event Store ✅
		- Apache Kafka/Confluent
	- Architecture
	  collapsed:: true
		- Event Sourcing #event-sourcing
		- Micro Services
		- Monolithic
	- Languages
		- Haskell #lang-haskell
		- Clojure #lang-clojure
		- PHP #lang-php
			- Laravel #laravel
		- Dart #lang-dart
		- Go #lang-go
		- NodeJS #lang-nodejs
		- Elm #lang-elm
		- Elixir #lang-elixir
		- Rust #lang-rust
	- Specifications
		- HATEOS
			- JSON:API
			- HAL
			- Siren
			- JSON:LD
		- API Specs
			- OpenApi Specification #oas (Synchronous)
			- Async API #async-api (Asynchronous)
			-
-
- ## Introduction
	- The hardest parts of creating an application mainly has to do with the  backend. That is where the app lives. Get it right and your app can do it's job effectively and keep your users happy. Mess it up and you know that your business ==is doomed==. Like ==seriously==
	  id:: 63143a33-e485-41f7-862d-fcbc372018dc
	- And because of this, (Mobile)Backend As A Service(BaaS or MBaaS) #baas #saas #mbaas tools and platform are on the rise. All with the aim of providing you the solid platform to handle all your backend needs. These backend have the following ((631449e5-08fb-46ba-a130-5475da5c14ed))
	- Backend Features:
	  id:: 631449e5-08fb-46ba-a130-5475da5c14ed
		- Authentication
		- Authorisation
		- Database
		- Storage
		- Mailing
		- Geo location
		- Logging
		- API Interface (REST/GraphQL)
		- Payment Integration
		- USSD Integration
		- Web-hooks/Callback URL
		- Severless Functions
	- Most of these #baas provides SDKs or API to use these features from your frontend.
	- Popular #baas includes:
		- Firebase
		- Appwrite
		- Supabase
		- Nhost
		-
	- Business requirements may change any time and when it does, the developers have to go back to the codes, and apply the new changes.
	  id:: 63143985-2a98-4012-8e16-d90341226339
	- But the problem with these #baas is their one-size fits all solutions
	- They require you to write your app in  a certain way.
	- The Bullet-proof Application #🛡️bpa ensures that your application is resistant to any changes you throw at it.
	- It does this using code-generators special built for this tasks
- ## A peek into the Engine
	- Under the hood, the #🛡️bpa is powered by #headless modules which is derived from an extendable #oas or #async-api schema documentation and special-purpose generators.
	- For each of these ((631449e5-08fb-46ba-a130-5475da5c14ed)), a headless module will be made available. These headless modules are themselves generated from an #oas or #async-api schema.
	- You can extend these modules by extending from the #headless modules specifications and add your business specific requirements.
	-
	- You select the #headless modules you want to use, which will be feed into the backend-generator
	- The generator shall consist of the following:
		- Using pre-built #headless modules, the generator composes the backend.
		- Each #headless module shall have a Schema specification which is used to generate the API.
		- An API generated should be able to scaffold both REST and GraphQL APIs
	- You create a Schema specification using any of these two (2) specs using the latest versions and feed them into the generator
	- The generator takes in these specs to generate the application
- ## Suggestions
	- "implement" is wordy or unneeded [🔖](63143985-2a98-4012-8e16-d90341226339)
	- "is doomed" may be passive voice [🔖](63143a33-e485-41f7-862d-fcbc372018dc)
	- "seriously" can weaken meaning [🔖](63143a33-e485-41f7-862d-fcbc372018dc)
	- "usually" can weaken meaning [🔖](63143bfb-5f7d-461e-bdee-e193dd29895b)