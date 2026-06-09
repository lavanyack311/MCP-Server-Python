# MCP Documentation Search Server

A custom Model Context Protocol (MCP) server built with Python and FastMCP that enables Claude Desktop to search and retrieve the latest technical documentation from popular developer platforms such as OpenAI, LangChain, LlamaIndex, and UV.

## Overview

This project demonstrates how to build a production-ready MCP server that integrates external search APIs, fetches documentation from the web, processes content, and exposes it as tools that can be used directly within Claude Desktop.

The server uses the Google Serper API to discover relevant documentation pages, retrieves content asynchronously using `httpx`, cleans and processes web pages, and returns documentation results to Claude through the Model Context Protocol.

## Features

* Search official documentation from multiple developer platforms
* Integrate Claude Desktop with custom MCP tools
* Fetch documentation content asynchronously
* Process and clean web content for AI consumption
* Support multiple documentation providers
* Environment variable management using `.env`
* Robust error handling and request timeouts
* Lightweight and extensible architecture

## What You'll Learn

### 1. Modern Python Development with UV

Learn how to use the UV package manager to:

* Create and manage Python virtual environments
* Install dependencies efficiently
* Maintain reproducible development environments
* Manage project dependencies through `pyproject.toml`

### 2. Building MCP Servers

Understand the fundamentals of the Model Context Protocol:

* Creating MCP servers using FastMCP
* Registering tools with decorators
* Exposing functionality to AI assistants
* Running MCP servers over standard I/O transport

### 3. Documentation Search with Google Serper API

Implement web search capabilities by:

* Connecting to the Serper API
* Performing targeted documentation searches
* Filtering results from official documentation sources
* Returning relevant documentation links

### 4. Web Scraping and Content Processing

Learn how to:

* Retrieve web pages programmatically
* Extract meaningful content from HTML
* Clean and normalize documentation text
* Prepare content for AI consumption

### 5. Claude Desktop Integration

Configure Claude Desktop to:

* Connect to custom MCP servers
* Discover available tools
* Invoke documentation search capabilities
* Extend Claude with custom functionality

### 6. Asynchronous Programming

Use Python's async ecosystem to:

* Perform concurrent web requests
* Improve application responsiveness
* Handle network operations efficiently
* Scale documentation retrieval workflows

### 7. Error Handling and Reliability

Implement best practices such as:

* API request validation
* Timeout management
* Graceful error handling
* Fault-tolerant network communication

## Technologies Used

* Python 3.10+
* Model Context Protocol (MCP)
* FastMCP
* UV Package Manager
* Claude Desktop
* Google Serper API
* HTTPX
* BeautifulSoup
* AsyncIO
* Python Dotenv

## Use Cases

* AI-powered documentation search
* Developer productivity tools
* Knowledge retrieval systems
* Custom Claude Desktop integrations
* Internal documentation assistants
* AI-enhanced developer workflows
