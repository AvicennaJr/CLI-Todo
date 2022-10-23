# CLI To Do App

This is a simple blazingily fast ToDo Command Line App made with Go.

## How to Install

You can download the binary on the release page or download the source code and
compile your own with:

`go build cmd/todo/main.go`

## How to Use

These are the following options:

<pre>
-h : To show the help message
-add: To add a new task
-list: To list all tasks in the todo list
-complete: To mark a task in the todo list as complete
-delete: To delete a task from the list
</pre>

## Examples

Here are a few examples:

<pre>
// Add an item
todoApp -add This is my first task
todoApp -add This is my second task

// List all tasks
todoApp -list

//output
1: This is my first task
2: This is my second task

// Mark a task as complete

todoApp complete 1

//output
X 1: This is my first task
  2: This is my second task

// Delete a task from the list

todoApp -delete 1

//output

1: This is my second task
</pre>

## License

No license at the moment XD
