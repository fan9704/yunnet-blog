![](./doc/Banner.png)

# 國立雲林科技大學-宿舍網路管理小組 部落格
---

## 介紹

這是一個提供許多網管小組的成員參考各式外修或是社團營運的集成筆記

---

## 核心技術

> Hexo MarkDown

---

## 使用方法

### 1. Clone 本專案

```shell
git clone git@github.com:fan9704/yunnet-blog.git
```

### 2. 安裝依賴

```shell
yarn install
```

### 3. 下載主題

在專案資料夾內
```shell
git clone <主題位置> themes/ocean
```

### 4. 新增文章

```shell
hexo new <文章名稱>
```

### 5. 產生靜態文件

```shell
hexo g -c 
```

### 6. 部屬至 GitHub Pages 

```shell
hexo deploy
```