ARG version
FROM almalinux:${version:-9}
ARG course="devops" \
    duration="120hrs"
    # access arg values in inside container
ENV duration=$duration 
RUN echo "Course: $course, duration: $duration"
CMD [ "sleep", "100" ]