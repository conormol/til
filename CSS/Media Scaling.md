# Media Scaling

When scaling media (i.e images and videos, a common design pattern is to put the media inside a container div. The container would have a responsive width and a fixed height, with the overflow set to hidden. The media itself would have its maximum width set to 100% of the container, and would be displayed as a block level element.

``
container {
  width: 50%;
  height: 200px;
  overflow: hidden;
  }
  
container img {
  max-width: 100%;
  height: auto;
  display: block;
  }
``
