Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the 1upd tests manually, launch src/test/test_1up .

To add more 1upd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the 1up-qt tests manually, launch src/qt/test/1up-qt_test

To add more 1up-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
