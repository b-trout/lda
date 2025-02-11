.. _whats_new:

.. currentmodule:: lda

============
 What's New
============

v3.0.1 (19. June 2024)
======================
- Drop support for Python 3.9.
- Construct nzw in fortran order to reduce cache misses in hot loops. Thanks @ghuls.

v3.0.0 (4. December 2023)
============
- Drop support for Python 3.6, 3.7 and 3.8
- Wheels for Python 3.9, 3.10, 3.11 and 3.12

v2.0.0 (17. August 2020)
==========================
- Drop support for Python 2.7
- Wheels for Python 3.8

v1.1.0 (9. September 2018)
==========================
- Wheels for Python 3.7
- Minimum required NumPy version is 1.13.0.
- Major speed increase in data loading. Thanks @luoshao23.
- Bugfix in Cython searchsorted function. Thanks @luoshao23.

v1.0.5 (18. June 2017)
======================
- Wheels for Python 3.6

v1.0.4 (13. July 2016)
======================
- Linux wheels (manylinux1)

v1.0.3 (5. Nov 2015)
====================
- Python 3.5 wheels
- Release GIL during sampling
- Many minor fixes
