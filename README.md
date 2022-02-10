# gor
Script for opening the most commonly used github paths from CLI in MAC

## Usage
Run this on your MAC CLI

```
git clone git@github.com:doshinwills-okta/gor.git
cp ./gor/gor ~/.gor
echo 'source ~/.gor' >>~/.bash_profile
source ~/.bash_profile
```

### Commands

#### Goto remore repo
```
gor o
gor 1
```

#### Goto remote repo with the current working folder
```
gor cd
gor 2
```
#### Goto remote current branch
```
gor cb
gor 3
```

#### Goto remote current branch in bacon
```
gor cb b
gor 3 b
```

#### Create pr for current branch
```
gor cpr
gor 4
```
#### Goto current commit
```
gor cc
gor 5
```

#### Goto current commit in bacon
```
gor cc b
gor 5 b
```

#### Goto my open prs
```
gor moprs
gor 6
```

#### Goto my closed prs
```
gor mcprs
gor 7
```

#### Goto open prs
```
gor oprs
gor 8
```

#### Goto closed prs
```
gor cprs
gor 9
```