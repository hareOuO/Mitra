# # Makefile

# .PHONY: all clean

# # 默认目标：调用 SCons 构建系统
# all:
# 	@scons lib$(SCONSFLAGS)


# install:

# # 清理构建文件：调用 SCons 的 clean
# clean:
# 	@scons lib -c $(SCONSFLAGS)

# Makefile

.PHONY: all clean install

# 默认目标：调用 SCons 构建系统，强制使用静态链接
all:
	@scons lib static_relic=1 $(SCONSFLAGS)

# 安装目标（可根据需要补充实际安装逻辑）
install:
	@echo "Install not implemented."

# 清理构建文件：调用 SCons 的 clean，强制使用静态链接
clean:
	@scons lib -c static_relic=1 $(SCONSFLAGS)