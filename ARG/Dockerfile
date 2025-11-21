# ARG VERSION
# FROM almalinux:${VERSION:-9}

ARG VERSION
FROM almalinux:${VERSION:-9}

ARG COURSE_NAME="Docker" \
    TRAINER_NAME="SivaKumar"

RUN echo "Course= ${COURSE_NAME}, Trainer= ${TRAINER_NAME}, Version= ${VERSION}"

CMD ["sleep", "1000"]