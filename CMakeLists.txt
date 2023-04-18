cmake_minimum_required(VERSION 3.0)
project(test_me)

include(FetchContent)

FetchContent_Declare(
    vpux_emulator
    GIT_REPOSITORY git@github.com:intel-innersource/applications.ai.vpu-accelerators.vpux-emulator.git
    GIT_TAG        d900e532a6b6ea0f22876341b5102265738e4a10
)
FetchContent_MakeAvailable(vpux_emulator)