# Automatic iframe resizing

Here we provide you with an example of how an iframe can report its height
to the parent window. The solution is compatible with IE10.

The process is the following:

1. The parent window subscribes to window events of the iframe.
1. The iframe returns its height onload and on turbolinks events (optional).
1. The parent sets the height of the iframe element.

