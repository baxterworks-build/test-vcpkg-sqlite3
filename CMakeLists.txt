cmake_minimum_required(VERSION 3.23)

project(something VERSION 1.0
DESCRIPTION "test"
LANGUAGES C)

find_package(unofficial-sqlite3 CONFIG REQUIRED)