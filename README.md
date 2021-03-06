![](https://dev.lutece.paris.fr/jenkins/buildStatus/icon?job=myapps-plugin-avatar-deploy)
# Avatar plugin

## Introduction

This plugin allows to insert into contents, typically comments the public avatar (photo or other) of its author.

It has an avatar provider implementation to recover them from the site Gravatar.com.

![](https://dev.lutece.paris.fr/plugins/plugin-avatar/images/gravatar.jpg)

## Configuration

The implementation is defined in the file `avatar_context.xml` . The default implementation is based on Gravatar.

Default avatars are defined in the file `gravatar.properties` 
 `
```
# avatar properties file

#######################################################################################################
# Default values
#
# mm: (mystery-man) a simple, cartoon-style silhouetted outline of a person (does not vary by email hash)
# identicon: a geometric pattern based on an email hash
# monsterid: a generated 'monster' with different colors, faces, etc
# wavatar: generated faces with differing features and backgrounds
# retro: awesome generated, 8-bit arcade-style pixelated faces
# blank: a transparent PNG image (border added to HTML below for demonstration purposes)

avatar.gravatar.default=mm
                    
```
` 
## Usage

This plugin is used by Digglike and ExtendComment.


[Maven documentation and reports](https://dev.lutece.paris.fr/plugins/plugin-avatar/)



 *generated by [xdoc2md](https://github.com/lutece-platform/tools-maven-xdoc2md-plugin) - do not edit directly.*