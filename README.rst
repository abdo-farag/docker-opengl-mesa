docker-opengl-mesa
==================

Builds a Docker image that allows sharing the local X display for graphical
apps on a system that uses the Mesa OpenGL implementation (Intel graphics,
etc). OpenGL and DRI direct hardware acceleration are supported.

Requires Docker 1.3.0 or greater.

.. attention::

  This approach for using graphical applications in Docker is highly
  discouraged. The resulting Docker image will not be portable; it depends
  both on the host graphics device and the graphics driver version. Instead
  the `thewtex/opengl <https://github.com/thewtex/docker-opengl>` Docker image
  is recommended.
