<template>
	<div>
		<Container align="center" padding="32">
			<h1 class="text-6xl leading-tight font-bold mb-4">Build better interfaces with Neutron UI</h1>
			<p class="leading-relaxed text-gray-700 text-xl mb-8">Dozens of responsive HTML components built with TailwindCSS & VueJS, published free by the team at Neutron Creative, in our mission to make the world open-source.</p>
			<div class="flex flex-row items-center justify-center mb-4">
				<n-link to="/library">
					<Button size="lg" class="mb-2 md:mb-0 md:mr-4">Browse components</Button>
				</n-link>
				<a href="https://github.com/Neutron-Creative/Neutron-UI">
					<Button size="lg" background="indigo-600">Download for free</Button>
				</a>
			</div>
			<n-link class="text text-gray-600 hover:underline" to="">
				<span>Currently v0.1.0. Last updated on September 28, 2020</span>
			</n-link>
		</Container>
		<Container align="left" background="white">
				<h2 class="text-center font-semibold text-4xl text-gray-900" data-aos="fade-up" data-aos-duration="1000">Get started in 30 seconds</h2>
				<Container width="full" padding="0" mobile-padding="0" direction="row" background="white">
					<div class="flex w-full lg:w-5/12 p-6">
						<form data-aos="fade-up" data-aos-duration="1000" style="transform:perspective(1040px) rotate(0deg) rotateX(-2deg) rotateY(12deg) translateZ(10px) scale(1.05); " class="shadow-lg relative w-full min-w-sm max-w-sm mt-4 p-6 bg-white rounded-md shadow-md flex-col">
							<div class="w-full h-full absolute t-0 l-0 r-0 b-0 z-1"></div>
							<svg class="mb-2 ml-auto mr-auto" style="max-width: 185px;" id='logoipsum' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 177.778 100'><path d='M40.99,58.759,23.05,46.384c-1.818-1.254-1.2-3.865,1.067-4.479L43.184,36.73A2.7,2.7,0,0,1,46.8,39.222L45.67,56.771C45.536,58.854,42.808,60.013,40.99,58.759Z' fill='#e9327c'/><path d='M35.3,61.814,24.731,41.145a2.883,2.883,0,0,1,3.007-4.161l19.587,3.023a2.883,2.883,0,0,1,2.127,4.162L40.429,61.815A2.883,2.883,0,0,1,35.3,61.814Z' fill='#1dace3'/><path d='M46.752,39.918l-9.764-1.507L25,41.666l4.785,9.361L40.99,58.759a2.888,2.888,0,0,0,.806.383l4.256-8.323Z' fill='#001a49'/><path d='M96.209,42.334a1.835,1.835,0,1,1,1.835,1.835A1.854,1.854,0,0,1,96.209,42.334Zm.306,2.732h3.059V55.26H96.515Z' fill='#001a49'/><path d='M112.784,50.163a5.119,5.119,0,0,1-4.872,5.383,3.829,3.829,0,0,1-3.038-1.244v5.036h-3.058V45.066h3.058v.958a3.829,3.829,0,0,1,3.038-1.243A5.118,5.118,0,0,1,112.784,50.163Zm-3.058,0a2.427,2.427,0,1,0-2.426,2.488A2.327,2.327,0,0,0,109.726,50.163Z' fill='#001a49'/><path d='M122.223,52.2c0,2.345-2.039,3.344-4.241,3.344a4.463,4.463,0,0,1-4.383-2.427l2.65-1.508a1.675,1.675,0,0,0,1.733,1.2c.734,0,1.1-.225,1.1-.632,0-1.122-5.015-.53-5.015-4.058,0-2.222,1.875-3.343,4-3.343a4.46,4.46,0,0,1,3.975,2.181l-2.609,1.407a1.481,1.481,0,0,0-1.366-.9c-.53,0-.856.2-.856.571C117.208,49.205,122.223,48.43,122.223,52.2Z' fill='#001a49'/><path d='M133.4,45.066V55.26h-3.058V54.3a3.489,3.489,0,0,1-2.916,1.244c-2.059,0-3.812-1.468-3.812-4.221V45.066h3.058v5.811a1.681,1.681,0,0,0,1.774,1.855c1.121,0,1.9-.652,1.9-2.1V45.066Z' fill='#001a49'/><path d='M150.928,49V55.26H147.87V49.266c0-1.019-.49-1.672-1.468-1.672-1.02,0-1.59.714-1.59,1.917V55.26h-3.059V49.266c0-1.019-.489-1.672-1.468-1.672-1.019,0-1.59.714-1.59,1.917V55.26h-3.058V45.066H138.7V46a3.129,3.129,0,0,1,2.732-1.223,3.034,3.034,0,0,1,2.671,1.345,3.359,3.359,0,0,1,2.957-1.345C149.4,44.781,150.928,46.452,150.928,49Z' fill='#001a49'/><circle cx='153.519' cy='42.733' r='2.27' fill='#001a49'/><path d='M54.457,40.377h3.059V55.26H54.457Zm4.791,9.786a5.4,5.4,0,1,1,5.4,5.383A5.343,5.343,0,0,1,59.248,50.163Zm7.748,0a2.345,2.345,0,1,0-2.345,2.406A2.287,2.287,0,0,0,67,50.163Zm15.249-5.1v9.685c0,3.425-2.671,4.872-5.382,4.872a5.212,5.212,0,0,1-4.832-2.467l2.609-1.509a2.331,2.331,0,0,0,2.325,1.285,2.032,2.032,0,0,0,2.3-2.181v-.938a3.622,3.622,0,0,1-2.977,1.325,5.181,5.181,0,0,1,0-10.357,3.622,3.622,0,0,1,2.977,1.325v-1.04Zm-2.976,4.893A2.47,2.47,0,1,0,76.8,52.325,2.308,2.308,0,0,0,79.269,49.959Zm4.708.2a5.4,5.4,0,1,1,5.4,5.383A5.343,5.343,0,0,1,83.977,50.163Zm7.748,0a2.346,2.346,0,1,0-2.345,2.406A2.287,2.287,0,0,0,91.725,50.163Z' fill='#001a49'/></svg>              <div class="flex flex-col mb-4">
							<label class="font-medium text-sm">Email Address</label>
							<input class="p-2 mt-2 text-sm border-solid border-gray-200 rounded-sm border" type="email" placeholder="e.g. jane@gmail.com"/>
						</div>
							<div class="flex flex-col mb-4">
								<label class="font-medium text-sm text-gray-800">Handle</label>
								<div class="flex flex-row p-2 pl-0 pt-0 pr-0 pb-0 mt-2 text-sm border-solid border-gray-200 rounded-sm border">
									<span class="flex p-2 bg-gray-100 border text-gray-700 border-solid border-gray-300 border-t-0 border-l-0 border-b-0">@</span>
									<input class="p-2 flex-grow w-full" type="text" name="handle" id="handle" placeholder="e.g. janedoe"/>
								</div>
							</div>
							<div class="flex flex-col mb-4">
								<label class="font-medium text-sm">Password</label>
								<input class="p-2 mt-2 text-sm border-solid border-gray-200 rounded-sm border" type="password" placeholder="e.g. your password"/>
							</div>
							<button type="button" class="mt-2 w-full p-3 text-center text-sm text-white bg-indigo-600 hover:bg-indigo-700 rounded-sm font-semibold">Sign up</button>
						</form>
					</div>
					<div class="flex flex-col w-full lg:w-7/12 p-6 mb-2">
						<div data-aos="fade-up" data-aos-duration="1000" class="p-6 hover:bg-gray-100 rounded cursor-pointer">
							<h3 class="font-semibold text-xl mb-2 text-gray-900">Build responsive interfaces in minutes</h3>
							<p class="text-gray-700 leading-relaxed">View our component library and copy your favorite components for your application in seconds, no download required.</p>
						</div>
						<div data-aos="fade-up" data-aos-duration="1000" class="p-6 hover:bg-gray-100 rounded cursor-pointer">
							<h3 class="font-semibold text-xl mb-2 text-gray-900">Easy to get started, no installation required</h3>
							<p class="text-gray-700 leading-relaxed">Our library is based on TailwindCSS & VueJS (optional), meaning there are no additional dependencies or installation required.</p>
						</div>
						<div data-aos="fade-up" data-aos-duration="1000" class="p-6 hover:bg-gray-100 rounded cursor-pointer">
							<h3 class="font-semibold text-xl mb-2 text-gray-900">Build and customize without limits</h3>
							<p class="text-gray-700 leading-relaxed">Utilize the full power of TailwindCSS and brand your application in seconds with customizable colors, fonts, and more easily accessible in the Tailwind CSS configurations file.</p>
						</div>
					</div>
				</Container>
		</Container>
		<Container direction="row">
				<div class="flex flex-col p-4">
					<h2 class="font-semibold text-4xl text-gray-900 mb-4" data-aos="fade-up" data-aos-duration="1000">Ready to get started?</h2>
					<p class="text-gray-700 text-lg">
						Neutron UI is 100% free and no installation is required.
					</p>
				</div>
				<div class="flex flex-col p-4 ml-auto">
					<n-link to="/library" class="w-full">
						<Button class="mb-2 w-full">Browse components</Button>
					</n-link>
					<a href="https://github.com/Neutron-Creative/Neutron-UI" class="w-full">
						<Button class="w-full" background="indigo-600">Download for free</Button>
					</a>
				</div>
		</Container>
	</div>
</template>
<script>
    import Container from "../components/Container";
    export default {
        components: {Container},
        head: {
            title: 'Neutron UI - A free and open-source UI kit for TailwindCSS'
        },
	    layout: 'landing-page'
    };
</script>
