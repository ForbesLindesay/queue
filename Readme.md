
# queue

  Simple JavaScript queue

## Installation

    $ component install ForbesLindesay/queue

## API

### queue()

  Call `queue()` to create a new queue object:

  ```javascript
  var queue = require('queue');
  var myQueue = queue();
  ```
### queue(mixin)

  You can also use `queue(mixin)` as a mixin:

  ```javascript
  var queue = require('queue');
  queue(myObject);
  ```

### queue#enqueue(item)

  Adds a new item to the queue, and returns the queue for chaining.

### queue#dequeue()

  Returns the next item in the queue, and remove it.

### queue#peek()

  Returns the next item in the queue, without removing it.

### queue#isEmpty()

  Returns `true` if there are no items left in the queue.

## License

  MIT
