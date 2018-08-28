---
swagger: "2.0"
x-collection-name: Codefresh
x-complete: 0
info:
  title: Codefresh Post Provers Github Hook
  description: Post provers github hook.
  termsOfService: http://www.codefresh.io
  contact:
    name: Codefresh api team
    url: http://www.codefresh.io
  version: 1.0.0
host: g.codefresh.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/github/hook:
    post:
      summary: Post Provers Github Hook
      description: Post provers github hook.
      operationId: postProversGithubHook
      x-api-path-slug: providersgithubhook-post
      parameters:
      - in: body
        name: after
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: commits
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: head_commit
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: ref
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: repository
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: send-mail-and-update-github
        description: will this hook send notification to related users
      - in: body
        name: sender
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: x-github-delivery
        description: the id from github
      - in: header
        name: x-github-event
        description: event type of this hook
      - in: header
        name: x-github-signature
        description: the signature from github
      responses:
        200:
          description: OK
      tags:
      - Provers
      - Github
      - Hook
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---