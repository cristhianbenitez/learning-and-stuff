# Asynchronous

JavaScript is a synchronous language, it has a so called run-to-completion semantics.Meaning, the current task is always finished before the next task is executed.

Therefore when you're working with asynchronous promise-based API's that run on the event loop until completion before sending any response, Javascript use the `async / await` function that let's you run the code and wait until completion before going to the next task.
