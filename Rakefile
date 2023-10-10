desc 'Create template of yatteiki.md'
task :create_template do
  joining_year = Time.now.year
  print('社員番号(例:999)：')
  employee_number = STDIN.gets.chomp
  print('氏名(ローマ字)(例:Pepa_Taro)：')
  full_name = STDIN.gets.chomp
  path = "./#{joining_year}/#{employee_number}_#{full_name}/"
  FileUtils.mkdir_p(path) unless FileTest.exist?(path)
  open("#{path}yatteiki.md", 'w'){|f|
    f.write('# ペパボで私がやっていきたいこと')
    f.write("\n\n")
    f.write('## 1ヶ月後の目標')
    f.write("\n\n")
    f.write('## 2ヶ月後の目標')
    f.write("\n\n")
    f.write('## 3ヶ月後の目標')
    f.write("\n\n")
    f.write('# 振り返り')
    f.write("\n\n")
    f.write('## Month 1')
    f.write("\n\n")
    f.write('TBE')
    f.write("\n\n")
    f.write('## Month 2')
    f.write("\n\n")
    f.write('TBE')
    f.write("\n\n")
    f.write('## Month 3')
    f.write("\n\n")
    f.write('TBE')
    f.write("\n\n")
    f.write('# ペパボテックカンパニービジョンの感想')
    f.write("\n\n")
    f.write('xxxx は yyyy なので zzzz と思った。')
    f.write("\n")
  }
end
