<script>
	import { Breadcrumb, BreadcrumbItem, Heading } from 'flowbite-svelte';
	import EmptyCard from './EmptyCard.svelte';
	import { Card, Dropdown, DropdownItem, Avatar, Button } from 'flowbite-svelte';
	import { DotsHorizontalOutline } from 'flowbite-svelte-icons';
</script>

<main>
	<div class="grid grid-cols-1 pt-2 dark:bg-gray-900 xl:grid-cols-3 xl:gap-4 xl:px-0">
		<div class="col-span-full mb-4 xl:mb-2">
			<Breadcrumb class="mb-5">
				<BreadcrumbItem href="/" home>Home</BreadcrumbItem>
				<BreadcrumbItem href="/">Pages</BreadcrumbItem>
				<BreadcrumbItem>Playground</BreadcrumbItem>
			</Breadcrumb>
			
		</div>
		
		<div class="col-span-full xl:col-auto">
			<Card size="xl" class="mb-4 h-80 w-full space-y-6 2xl:col-span-2" >
				<div class="flex flex-col items-center pb-4">
				  <Avatar size="xl" class="mb-7" src="/images/my-logo.png" />
				  <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Vasily Prokhozhev</h5>
				  <span class="text-sm text-gray-500 dark:text-gray-400">Aspiring software developer</span>
				  <div class="flex mt-4 space-x-3 rtl:space-x-reverse lg:mt-6">
				  </div>
				</div>
			  </Card>
		</div>

		<div class="col-span-2">
			<EmptyCard size="none" class="mb-4 h-80 w-full space-y-6"></EmptyCard>
			<EmptyCard size="none" class="mb-4 h-80 w-full space-y-6"></EmptyCard>
		</div>
	</div>

</main>

