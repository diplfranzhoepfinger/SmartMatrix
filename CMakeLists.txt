# SmartMatrix Library
# https://github.com/pixelmatix/SmartMatrix
# 

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRC_DIRS "src"
                       INCLUDE_DIRS "src"
                       REQUIRES driver arduino Adafruit-GFX-Library Adafruit_BusIO)

project(SmartMatrix)
