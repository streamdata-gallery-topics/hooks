swagger: "2.0"
x-collection-name: GitHub
x-complete: 1
info:
  title: GitHub
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repos/{owner}/{repo}/hooks:
    get:
      summary: Get Repos Owner Repo Hooks
      description: Get list of hooks.
      operationId: get-list-of-hooks
      x-api-path-slug: reposownerrepohooks-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
    post:
      summary: Add Repos Owner Repo Hooks
      description: Create a hook.
      operationId: create-a-hook
      x-api-path-slug: reposownerrepohooks-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
  /repos/{owner}/{repo}/hooks/{hookId}:
    delete:
      summary: Delete Repos Owner Repo Hooks Hook
      description: Delete a hook.
      operationId: delete-a-hook
      x-api-path-slug: reposownerrepohookshookid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: hookId
        description: Id of hook
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
      - Hook
    get:
      summary: Get Repos Owner Repo Hooks Hook
      description: Get single hook.
      operationId: get-single-hook
      x-api-path-slug: reposownerrepohookshookid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: hookId
        description: Id of hook
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
      - Hook
    patch:
      summary: Patch Repos Owner Repo Hooks Hook
      description: Edit a hook.
      operationId: edit-a-hook
      x-api-path-slug: reposownerrepohookshookid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: hookId
        description: Id of hook
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
      - Hook
  /repos/{owner}/{repo}/hooks/{hookId}/tests:
    post:
      summary: Add Repos Owner Repo Hooks Hook Tests
      description: |-
        Test a push hook.
        This will trigger the hook with the latest push to the current repository
        if the hook is subscribed to push events. If the hook is not subscribed
        to push events, the server will respond with 204 but no test POST will
        be generated.
        Note: Previously /repos/:owner/:repo/hooks/:id/tes
      operationId: test-a-push-hookthis-will-trigger-the-hook-with-the-latest-push-to-the-current-repositoryif-the-hook
      x-api-path-slug: reposownerrepohookshookidtests-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: hookId
        description: Id of hook
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Hooks
      - Hook
      - Tests