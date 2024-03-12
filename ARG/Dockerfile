FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG COURSE
RUN echo "course: ${COURSE}"
ENV COURSE=${COURSE}
cmd ["sleep", "100"]