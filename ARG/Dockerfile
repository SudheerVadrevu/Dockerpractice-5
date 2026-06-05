ARG version
FROM almalinux:${version:-9.2}
ARG sudheer=lazyboy
ARG vineela=hardwomen
ENV train=nandedexpress
RUN echo "sudheer is ${sudheer} vineela is ${vineela} train is ${train} "
CMD ["sleep", "100"]
# How can you check the version of OS in server? cat /etc/*release
# Here ${version:-9.2} this syntax will represents default version incase if user forgot to give
# this syntax only applicable for FROM Ins. If you use ARG anywhere in image then it won't applicable