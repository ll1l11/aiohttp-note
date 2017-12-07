The best place for connecting to DB is
:attr:`~aiohtp.web.Application.on_startup` signal::

   app.on_startup.append(init_pg)

on_startup_

.. _on_startup: https://docs.aiohttp.org/en/stable/tutorial.html?highlight=on_startup

优雅关闭应用:

https://docs.aiohttp.org/en/stable/web.html#graceful-shutdown

Nested applications:

https://docs.aiohttp.org/en/stable/web.html#nested-applications
