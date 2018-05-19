Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the nuyuld tests manually, launch src/test/test_nuyul .

To add more nuyuld tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the nuyul-qt tests manually, launch src/qt/test/nuyul-qt_test

To add more nuyul-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
