#-----------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See LICENSE in the project root for license information.
#-----------------------------------------------------------------------------------------

FROM google/dart:2

ENV PATH="$PATH":"/root/.pub-cache/bin"

RUN pub global activate webdev

# Install git, process tools
RUN apt-get update && apt-get -y install git procps

# Clean up
RUN apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*
	