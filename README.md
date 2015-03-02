# Puppet module for managing OpenLava

## Overview

Installs and configures OpenLava

## Usage

### openlava

Do stuff...

    class { 'openlava':
      clusters => [
        'hpc: node[00-99]',
      ],
    }

## Reference

### Classes

#### Public classes

* `openlava`: Installs and configures openlava

#### Private classes

* `openlava::params`: Defines default parameter values

#### openlava

#####`Administrators`

The list of administrators to use. Default is 'openlava'
