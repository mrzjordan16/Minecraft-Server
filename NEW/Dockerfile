FROM openjdk:18
WORKDIR /app
ENTRYPOINT ["java"]
CMD ["@user_jvm_args.txt" ,"@libraries/net/minecraftforge/forge/1.18.2-40.1.0/unix_args.txt","'$@'"]