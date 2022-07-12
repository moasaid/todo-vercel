<script>
	import TodoItem from '$lib/todo_item.svelte';

    const title = "Mo's Todos"
</script>

<svelte:head>
 <title>
    {title}
 </title>
</svelte:head>

<div>
    <h1>{title}</h1>

    <form action="" method="">
        <input type="text" name="text" aria-label="Add a todo" placeholder="+ type a ToDo">
    </form>

    <TodoItem />
    <TodoItem />
    <TodoItem />
</div>
