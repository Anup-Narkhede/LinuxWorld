# Crontab

Crontab is a list of commands that you want to run on a regular schedule.

## Syntax

Check [Documentations](https://www.computerhope.com/unix/ucrontab.htm).

```bash
MIN HOUR DOM MON DOW CMD
```

## Usage

| Field Name     | Allowed Value                  |
| -------------- | ------------------------------ |
| `minute`       | 0-59                           |
| `hour`         | 0-23                           |
| `day of month` | 1-31                           |
| `month`        | 1-12 or jan, feb               |
| `day of week`  | 0-7 or three character mon,tue |

Ranges and Lists

```bash
1,3,6,9
```

```bash
0-3,6-9
```

Unrestricted Range

```bash
*
```

Step Values

```bash
first-last/step
e.g. 0-12/2
o/p: 0,2,4,6,8,10,12
```

# Redirection

![Redirection](/Images/Redirection.png)
