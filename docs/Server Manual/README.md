---
sort: 1
---

# LDES Server Manual

The Linked Data Event Stream (LDES) server is a configurable component that can be used to ingest, store, transform and (re-)publish an LDES. The LDES server was built in the context of the VSDS project in order to easily exchange open data.


<!-- {% include list.liquid %} -->

- [Manual](https://xdxxxdx.github.io/githubpagesxd/Server%20Manual/configuration.html)
    - [Set-up of the LDES Server](https://xdxxxdx.github.io/githubpagesxd/Server%20Manual/configuration.html#set-up-of-the-ldes-server)
     -[How To Run]([#how-to-run](https://xdxxxdx.github.io/githubpagesxd/Server%20Manual/configuration.html#how-to-run)
        - [Locally](#locally)
            - [Maven](#maven)
            - [Profiles](#profiles)
            - [Application Configuration](#application-configuration)
                - [Example HTTP Ingest-Fetch Configuration](#example-http-ingest-fetch-configuration)
                - [Example Mongo Configuration](#example-mongo-configuration)
                - [Example Views Configuration](#example-views-configuration)
                - [Example Retention](#example-retention)
                - [Example Timebased Fragmentation](#example-timebased-fragmentation)
                - [Example Geospatial Fragmentation](#example-geospatial-fragmentation)
                - [Example Substring Fragmentation](#example-substring-fragmentation)
                - [Example Pagination](#example-pagination)
                - [Example Serving Static Content](#example-serving-static-content)
                - [Example Serving DCAT Metadata](#example-serving-dcat-metadata)
            -[Docker Setup](#docker-setup)
                - [Docker-compose](#docker-compose)
                - [The Config Files](#the-config-files)
                - [The docker compose File](#the-docker-compose-file)
                - [Starting the Dockerized Application](#starting-the-dockerized-application)
    - [Developer Information](https://xdxxxdx.github.io/githubpagesxd/Server%20Manual/configuration.html#developer-information)
                - [How To Build](#how-to-build)
                    - [How To Test and View Coverage](#how-to-test-and-view-coverage)
                        - [Unit and Integration Tests](#unit-and-integration-tests)
                        - [Only Unit Tests](#only-unit-tests)
                        - [Only Integration Tests](#only-integration-tests)
                        - [Auto-Configurable Modules](#auto-configurable-modules)
                    - [Tracing and Metrics](#tracing-and-metrics)
                        - [Local Tracing and Metrics](#local-tracing-and-metrics)
                        - [Using Docker](#using-docker)
                    - [Health and Info](#health-and-info)
                        - [Local Health and Info](#local-health-and-info)
                        - [Docker](#docker)`
