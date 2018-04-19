# st2-testCoordination-mistral
test code to demonstrate an issue with a mistral workflow calling st2-actions which are composed of another mistral workflow.
The issue occurs when the sub-workflow st2-action is cancelled by a policy, in which case the main workflow never ends and keeps on waiting for tasks to finish.

Used for reporting issue: https://github.com/StackStorm/st2/issues/4093
