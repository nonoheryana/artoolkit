add_subdirectory(collide)
add_subdirectory(exview)
add_subdirectory(loadMultiple)
add_subdirectory(modeTest)
add_subdirectory(multi)
add_subdirectory(optical)
add_subdirectory(paddle)
add_subdirectory(paddleDemo)
add_subdirectory(paddleInteraction)
add_subdirectory(range)
add_subdirectory(relation)
add_subdirectory(simple)
add_subdirectory(simple2)
add_subdirectory(simpleLite)
add_subdirectory(twoView)


if(OPENVRML_FOUND)
	add_subdirectory(simpleVRML)
endif(OPENVRML_FOUND)

