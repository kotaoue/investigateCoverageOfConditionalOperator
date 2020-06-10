# investigateCoverageOfConditionalOperator
Investigate coverage of conditional operator.

## Result
*
  ```
  ./vendor/bin/phpunit --bootstrap src/Target.php tests/TargetTest.php --coverage-html build/coverage-report
  ```  
  -> [result](build/coverage-report/)
* 
  ```
  phpdbg -qrr ./vendor/bin/phpunit --bootstrap src/Target.php tests/TargetTest.php --coverage-html build/coverage-report-phpdbg
  ```  
  -> [result](build/coverage-report-phpdbg/)