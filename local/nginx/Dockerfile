FROM nginx:1.17.4

# 维护者信息
MAINTAINER cary "289872225@qq.com"

LABEL Component="nginx" \
      Name="nginx-local" \
      Version="1.17.4" \
      Release="1.0.0"

# 指定本地配置文件根目录

# 替换nginx的默认配置文件
COPY nginx.conf /etc/nginx/nginx.conf

VOLUME ["/data"]

CMD ["nginx", "-g", "daemon off;"]