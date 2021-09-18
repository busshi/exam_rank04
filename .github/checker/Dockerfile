# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Dockerfile                                         :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: aldubar <aldubar@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/07/18 11:02:19 by aldubar           #+#    #+#              #
#    Updated: 2021/09/08 17:15:36 by aldubar          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

FROM		ubuntu:latest

RUN			apt update && apt install -y clang

WORKDIR		/.github/checker

ENTRYPOINT	[ "clang", "-Wall", "-Wextra", "-Werror", "microshell.c"]
