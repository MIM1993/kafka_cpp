cmake_minimum_required(VERSION 3.22.1)
project(test_kafka)

set(CMAKE_CXX_STANDARD 17)

add_executable(test_kafka kafkaproducer.cpp kafkaproducer.h)
target_link_libraries(test_kafka rdkafka++)
