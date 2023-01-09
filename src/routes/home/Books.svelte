<script lang="ts">
	const books: BookInfo[] = [
		{
			id: '1',
			title: 'Les Miserables',
			author: 'Victor Hugo',
			cover: 'https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781626864641/les-miserables-9781626864641_hr.jpg'
		},
		{
			id: '1',
			title: 'Les Miserables',
			author: 'Victor Hugo',
			cover: 'https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781626864641/les-miserables-9781626864641_hr.jpg'
		},
		{
			id: '1',
			title: 'Les Miserables',
			author: 'Victor Hugo',
			cover: 'https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781626864641/les-miserables-9781626864641_hr.jpg'
		},
		{
			id: '1',
			title: 'Les Miserables',
			author: 'Victor Hugo',
			cover: 'https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781626864641/les-miserables-9781626864641_hr.jpg'
		},
		{
			id: '1',
			title: 'Les Miserables',
			author: 'Victor Hugo',
			cover: 'https://d28hgpri8am2if.cloudfront.net/book_images/onix/cvr9781626864641/les-miserables-9781626864641_hr.jpg'
		}
	]
</script>

<div class="w-10/12 flex gap-12 flex-wrap">
	{#each books as book}
		<button
			class="flex flex-col gap-3 p-3 cursor-pointer rounded focus:bg-black/5"
		>
			<img src={book.cover} class="h-56 rounded shadow-xl" alt="" />
			<div class="text-center w-full">
				<div class="font-semibold">{book.title}</div>
				<div class="text-sm text-black/80">{book.author}</div>
			</div>
		</button>
	{/each}
</div>
