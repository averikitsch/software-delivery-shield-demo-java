# Copyright 2022 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Use the Eclipse Temurin base image.
FROM eclipse-temurin:17-jre

# Copy the packaged files over.
COPY /target /app/

# Starts java app with debugging server at port 5005.
ENTRYPOINT ["java", "-jar", "/app/frontend-1.0.jar"]