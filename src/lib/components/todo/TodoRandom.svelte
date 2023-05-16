<script>
import { todos } from "../../store/TodoStore";
</script>

<section class="todo-list">
 {#each $todos as todo}
  <p>{todo.text} - {todo.complete}</p>
 {/each}
</section>