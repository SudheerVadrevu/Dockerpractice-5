ARG version
FROM almalinux:${version:-8}
#How can you check OS of your server? cat /etc/*release
ARG kakinada=goodplace
ARG hyderabad=worstplace
ENV mumbai=Redlightarea
RUN echo "kakinada is $kakinada Hyderabad is $hyderabad and Mumbai is $mumbai "
CMD [ "sleep", "100" ]
# If you see the syntax given IN FROM "${version:-8}" this syntax only accessible for versions if you use ARG outside any where then this syntax will not be applicable
