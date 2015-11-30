# テーブル定義
## Users
- name: string
- email: string
- password: string
- organization: string
- profile: text
- works: string
- photo: text

## Prototypes
- user_id: integer
- catchcopy: string
- concept: text

## prototype_images
- prototype_id: integer
- image: text
- main_sub: string

## Likes
- prototype_id: integer
- user_id: integer

## Tags
- tag: string

## Comments
- user_id: integer
- prototype_id: integer
- comment: text