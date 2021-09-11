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
gor open
gor 1
```

#### Goto remote repo with the current working folder
```
gor opencd
gor 2
```
#### Goto remote current branch
```
gor currentbranch
gor 3
```

#### Create pr for current branch
```
gor createpr
gor 4
```

#### Goto my open prs
```
gor myopenprs
gor 5
```

#### Goto my closed prs
```
gor myclosedprs
gor 6
```

#### Goto open prs
```
gor openprs
gor 7
```

#### Goto closed prs
```
gor closedprs
gor 8
```

#### Goto remote branch
```
gor branch BRANH_NAME
gor 9 BRANH_NAME
```
